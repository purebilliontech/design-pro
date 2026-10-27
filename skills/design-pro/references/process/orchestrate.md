<!-- Design Council orchestration layer. Not a third-party playbook — written for this skill. -->

# Orchestrate a UI build

This is the **mandatory pipeline** for any request that builds, designs, or improves a **UI surface** — a page, screen, component, landing page, marketing site, app view, or dashboard. SKILL.md routes here before routing anywhere else for those requests.

It exists because the bundled playbooks already contain a strong anti-generic engine (`tastemaker`), but a passive switchboard lets the agent skip the steps that actually prevent generic output. This file turns the key.

Default behavior is **fully autonomous** — no required questions, no human round-trips. Grounding comes from references, web search, and scripts, not from interrogating the user.

## Scope — when this applies

| Request | Path |
|---|---|
| Build / design / improve a page, screen, component, landing page, app view, dashboard | **This pipeline (spine mandatory).** |
| Critique only, no change ("audit this", "why does this look AI-generated") | tastemaker `audit` verb or `ui-craft` `better-interface`. No build. |
| Pure Three.js / shader scene, virtual tour, motion showreel, web video | `motion-3d` playbook directly. **Spine does not apply.** |
| Game architecture, combat, VFX | `games` playbook directly. **Spine does not apply.** |
| SVG illustration style, a single generated illustration | `motion-3d` / `ideagram`. **Spine does not apply.** |
| Research, strategy, personas, "should we build this" | `process` playbook directly. No build. |

The spine is built for pages/screens/components. Forcing its real-pixel palette and landing-page narrative arc onto a combat system or a bare shader scene is the empty ceremony the skill's design explicitly forbids — don't.

## The pipeline

Paths below are relative to the design-council skill root. The tastemaker playbook is at `references/ui-craft/tastemaker/tastemaker.md`; its own `scripts/…` and `references/…` paths resolve inside `references/ui-craft/tastemaker/tastemaker.files/`.

### 1 — Read the intent (brief)

Surface type, audience, the feeling wanted, and any references the user supplied. Keep it to what you can infer plus at most one clarifying question. Do not interrogate — autonomy is the default.

### 2 — Spine: run the tastemaker build loop (non-optional)

Read `references/ui-craft/tastemaker/tastemaker.md` and run its build workflow (Steps 0–5). Two of its steps are the biggest levers against generic output and are **mandatory here — never skipped, never treated as advisory**:

- **The reference field (tastemaker Step 1.25).** Build `.tastemaker/reference-board.md` from real sources — the `inspo` MCP if connected, otherwise web search/fetch of real current sites. "Inferred, not viewed" is only legal when neither source is available this session, never as a shortcut.
- **Structure rotation (tastemaker Step 2.5).** Pick a macrostructure and archetypes by name, rotated against `.tastemaker/log.json` and `~/.tastemaker/structure-history.json`, and state the pick and narrative arc out loud. This is what stops the hero → 3-cards → testimonial → footer template that survives even a perfect palette.

Run the real scripts the playbook calls for (`extract_palette.py` / `generate_palette.py`, `check_contrast.py`, `check_structure_history.py`). They are deterministic grounding; prose is not a substitute.

### 3 — One page-build engine, never two

tastemaker from Step 2 is **the page-build engine**. Do not run a second engine over it.

- **`web-build` / `ui-craft` playbooks are aesthetic-lane references,** consulted to inform the spine's palette/structure/mood decisions — not run as a parallel builder.
- **Exception — a complete specialized engine.** When the user explicitly asks for a style that maps to a complete `web-build` engine (e.g. `build-awwwards-quality-sites`, `cinematic-scroll-storytelling`), that playbook becomes **the** engine instead of tastemaker's build loop. Still wrap it: run the **reference-field step at the front** (Step 2's grounding) and the **anti-slop gate at the back** (Step 4). One engine, grounded and gated.
- **`motion-3d`, GSAP, `games` are additive capabilities, not page engines.** A 3D hero, a scroll animation, a game widget layers alongside the chosen page engine as the concept calls for. They don't decide page palette/structure, so there's no conflict.

The failure this prevents: two engines each picking their own palette and structure, fighting over the page — which produces exactly the incoherent, generic output the skill exists to kill.

### 4 — Mandatory final gate

- **If the spine ran,** tastemaker's own script-backed close **is** the gate: `anti_slop_scan.py`, `audit_motion.py`, `check_component_coherence.py`, and the `anti-slop-checklist.md` sweep. Do not also run a second overlapping audit — that only produces contradictory verdicts.
- **If a specialist-only path ran** (a standalone motion-3d scene, say, with no tastemaker spine), run the MengTo gate instead: `audit-ai-design-slop` then `no-ai-design-slop` from `ui-craft`.

A failing gate means iterate, not ship.

## Acceptance — the forcing function is artifacts, not prose

"You MUST ground it" is soft. A UI build is **done only when these real artifacts exist**:

1. `.tastemaker/reference-board.md` — the reference field was actually built.
2. `.tastemaker/style-lock.md` containing a **contrast matrix** — the palette is a contract, grounded and legal.
3. A `.tastemaker/log.json` structure entry — a macrostructure was picked and rotated, not defaulted.
4. Clean `anti_slop_scan.py` output — the gate actually ran and passed.

If any is missing, the build is not done — go back and produce it. This is the test of whether the fix worked: no reference board and no structure-rotation entry means the engine was skipped, regardless of how the page looks at a glance.

## Optional — concept-pick mode (off by default)

Only when the user explicitly asks to choose between directions ("show me a few options first", "give me concepts to pick from"). Do not trigger it on a normal build.

It extends tastemaker's existing `comps` verb (`references/ui-craft/tastemaker/tastemaker.files/references/verbs/comps.md`), which already produces divergent directions from the palette + macrostructure engine. The difference: after the user picks a direction, **continue into the full build pipeline above** with that direction locked into `.tastemaker/style-lock.md`, rather than stopping at an image-generator brief as `comps` does today. One "give me options" path, not two.
