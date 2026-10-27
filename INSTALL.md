# Install

Three routes, easiest first.

## 1. As a skill (simplest — no plugin machinery)

Unzip, then copy the inner skill folder into your skills directory:

```bash
mkdir -p ~/.claude/skills
cp -r pure-billion-design/skills/design-council ~/.claude/skills/
```

Restart Claude Code. `design-council` now appears in your skill list, and the 328
playbooks sit behind it as reference files.

To scope it to one project instead, use `.claude/skills/` inside that repo.

## 2. As a local plugin

```bash
mkdir -p ~/.claude/plugins
cp -r pure-billion-design ~/.claude/plugins/
```

Restart Claude Code. Manage it from `/plugin`.

## 3. As a marketplace (to share with the team)

Push this folder to a GitHub repo your team can read. The repo already contains
`.claude-plugin/marketplace.json`, so teammates install with:

```
/plugin marketplace add <your-org>/<your-repo>
/plugin install pure-billion-design@pure-billion
```

This is the route to take if you want the whole team on the same version — publishing
to the org library directly isn't available from a cloud session yet, but a private
GitHub repo gets you the same outcome.

## Verifying it works

Ask Claude something like *"review this landing page's typography"* or *"this UI looks
AI-generated, fix it"*. It should load `design-council`, read
`references/ui-craft/INDEX.md`, and then open one or two specific playbooks — not the
whole library.
