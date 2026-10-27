---
name: design-pro
description: Routes design and front-end work to the right expert playbook from a bundled library of 328. Use for any UI, visual design, interaction, animation, typography, color, accessibility, layout, or copy work; for landing pages and design-engineering builds; for user research, personas, journey maps, usability tests, design systems, tokens, critique, and handoff; for Three.js and 3D scenes, motion showreels, video presentations, and SVG illustration; and for game architecture, combat, and VFX. Also use when asked to review, critique, or improve an existing interface, or when the request is "make this look better", "this looks AI-generated", "give it taste", or "which skill covers X".
---

# Design Pro

A routing layer over 328 design playbooks from seven published collections, with an orchestrated pipeline for UI builds on top. Each playbook is a self-contained reference file. **Read only the ones the task calls for** — never load the whole library.

## First fork: is this a UI build?

Before classifying, decide which of two paths the request is on. Getting this right is what separates distinctive output from generic output.

**Path A — Build / design / improve a UI surface** (a page, screen, component, landing page, marketing site, app view, or dashboard — and you will actually produce or change it):

→ **Read `references/process/orchestrate.md` and follow it.** It is the mandatory pipeline. It drives the bundled anti-generic engine (`tastemaker`) as a spine, routes the other areas in service of it, and enforces a final anti-slop gate. Do not hand a UI build straight to a single playbook — that is the passive-switchboard path that produces "any AI could have built this."

**Path B — everything else** (critique with no change, research and strategy, a pure Three.js / shader scene, a motion showreel, a game system, an SVG illustration, "which skill covers X"):

→ Use the switchboard below.

## Switchboard (Path B)

1. **Classify the request** into one of the five areas below.
2. **Read that area's `INDEX.md`.** It lists every playbook in the area with its full trigger description.
3. **Read the one or two playbooks that match.** Follow them as written — they are the expertise; this file is only the switchboard.
4. **If nothing matches**, say so and proceed with your own judgment rather than forcing a bad fit.

Reading two playbooks from different areas is normal and correct. Reading six is a sign the request needs splitting into stages.

## The five areas

| Area | Read when the work is about | Index |
|---|---|---|
| **ui-craft** (82) | Polish, typography, color systems, accessibility, layout, interface copy, interaction patterns, animation and motion feel, visual critique. The "does this look and feel right" layer. | `references/ui-craft/INDEX.md` |
| **web-build** (121) | Landing pages, marketing sites, design engineering, scroll and GSAP storytelling, turning references or screen recordings into prompts, page capture, article and image generation. The "build the page" layer. | `references/web-build/INDEX.md` |
| **process** (63) | User research, interviews, personas, JTBD, journey maps, surveys, usability testing, design systems governance, tokens, design ops, handoff specs, stakeholder and negotiation work. The "how the work gets decided" layer. | `references/process/INDEX.md` |
| **motion-3d** (36) | Three.js scenes, materials, lighting, water, god rays, virtual tours, motion showreels, web video presentations, and hand-written SVG illustration styles. | `references/motion-3d/INDEX.md` |
| **games** (26) | Game architecture, gameplay loops, combat systems, skill VFX, gameplay QA. | `references/games/INDEX.md` |

## Routing hints

These are the calls that are easy to get wrong:

- **"Make it look better" / "this looks AI-generated"** — if you'll actually change the UI, that's **Path A → `references/process/orchestrate.md`**. If it's critique only, that's `ui-craft` (tastemaker `audit` verb / `better-interface`).
- **"Review this interface"** (no change) → `ui-craft` (`better-interface` gives one ranked report across all six lenses).
- **Building a new marketing page** → **Path A → `references/process/orchestrate.md`.** Don't route straight to `web-build` + `ui-craft` as two separate engines; the orchestrator runs one engine, grounded and gated.
- **An animation feels wrong but you can't say why** → `ui-craft`, the animation playbooks. Easing and duration are usually the cause.
- **"Should we build this at all"** → `process`, not `ui-craft`. Research and strategy precede craft.
- **A static design that needs to become a video** → `motion-3d`.
- **Anything with a Figma file as input** → `web-build` (`build-design`).

## Supporting files

Some playbooks ship scripts and reference material alongside them, in a sibling folder named `<playbook>.files/`. When a playbook refers to its own references or scripts, look there. Demo assets (videos, screenshots, textures) were not bundled — if a playbook points at one, treat it as illustrative and carry on.

## Provenance

Every playbook carries a header naming its source repository and author. All seven collections are MIT licensed and bundled unmodified apart from that header:

| Collection | Author | Playbooks |
|---|---|---|
| MengTo/Skills | Meng To | 178 |
| Owl-Listener/designer-skills | MC Dean | 111 |
| emilkowalski/skills | Emil Kowalski | 15 |
| jakubkrehel/skills | Jakub Krehel | 14 |
| ConardLi/garden-skills | ConardLi | 6 |
| codeswithroh/tastemaker | codeswithroh | 2 |
| elayadesign/ai-design-skills | Elaya | 2 |

Keep attribution intact when quoting a playbook's content into client-facing work.
