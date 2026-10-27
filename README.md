# Design Pro

One skill. 328 design playbooks behind it — plus an orchestrator that drives them toward distinctive, non-generic UI.

Instead of installing 328 separate skills — which would flood the skill list and load
hundreds of descriptions into every conversation — this plugin registers a single
`design-pro` skill that routes to the right playbook on demand.

## Install

```
/plugin marketplace add purebilliontech/design-pro
/plugin install design-pro@design-pro
```

Then invoke it with `/design-pro`, or just ask for any UI/design work and it routes automatically.

## How it works

```
design-pro/
├── SKILL.md                         the router + first fork (UI build vs. everything else)
└── references/
    ├── process/orchestrate.md       the mandatory pipeline for UI builds
    ├── ui-craft/      (82)          polish, type, color, a11y, interaction, animation
    ├── web-build/     (121)         landing pages, design engineering, capture→prompt
    ├── process/       (63)          research, strategy, systems, ops, handoff
    ├── motion-3d/     (36)          Three.js, showreels, video, SVG illustration
    └── games/         (26)          architecture, combat, VFX, QA
```

For a build/design/improve request on a real UI surface, `SKILL.md` routes to
`references/process/orchestrate.md` — a pipeline that drives the bundled anti-generic
engine (`tastemaker`) as a mandatory spine, grounds the work in real references, rotates
page structure against defaults, and runs a final anti-slop gate before anything ships.
Everything else uses the plain switchboard: Claude reads the area's `INDEX.md`, picks one
or two playbooks, and loads only those.

## Sources

All seven source collections are MIT licensed. Every bundled playbook carries a header
naming its origin repository and author.

| Collection | Author |
|---|---|
| [MengTo/Skills](https://github.com/MengTo/Skills) | Meng To |
| [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills) | MC Dean |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | Emil Kowalski |
| [jakubkrehel/skills](https://github.com/jakubkrehel/skills) | Jakub Krehel |
| [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | ConardLi |
| [codeswithroh/tastemaker](https://github.com/codeswithroh/tastemaker) | codeswithroh |
| [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills) | Elaya |

The orchestration layer (`SKILL.md`'s first fork and `references/process/orchestrate.md`)
is original to this plugin; the 328 playbooks are bundled unmodified apart from an
attribution header.

## What was left out

Demo assets — videos, screenshots, 3D textures, example renders — were stripped.
They accounted for 163M of the 175M source material and none of them are needed for
a playbook to be followed. Scripts and reference markdown were kept.

## License

MIT. See the attribution headers in each bundled playbook for its original source.
