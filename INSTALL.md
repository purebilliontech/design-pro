# Install

Three routes, easiest first.

## 1. From the public marketplace (recommended)

```
/plugin marketplace add PureBillionTech/design-pro
/plugin install design-pro@design-pro
```

Then invoke with `/design-pro`, or just ask for any UI/design work and it routes
automatically.

## 2. As a skill (no plugin machinery)

Copy the inner skill folder into your skills directory:

```bash
mkdir -p ~/.claude/skills
cp -r design-pro/skills/design-pro ~/.claude/skills/
```

Restart Claude Code. `design-pro` now appears in your skill list, and the 328
playbooks sit behind it as reference files.

To scope it to one project instead, use `.claude/skills/` inside that repo.

## 3. As a local plugin

```bash
mkdir -p ~/.claude/plugins
cp -r design-pro ~/.claude/plugins/
```

Restart Claude Code. Manage it from `/plugin`.

## Verifying it works

Ask Claude something like *"review this landing page's typography"* or *"this UI looks
AI-generated, fix it"*. It should load `design-pro`, run the orchestration pipeline for a
real UI build (or read the right area's `INDEX.md` and open one or two playbooks for
everything else) — not the whole library.
