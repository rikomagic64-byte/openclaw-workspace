# OpenClaw Workspace

Private workspace for Kimmy and Nick.

## What this repo is

This repository stores the OpenClaw workspace files used for assistant identity, notes, memory, and future projects.

Current tracked files include:
- assistant/workspace guidance (`AGENTS.md`, `SOUL.md`, `TOOLS.md`)
- identity and user profile (`IDENTITY.md`, `USER.md`)
- heartbeat instructions (`HEARTBEAT.md`)
- selected memory notes (`memory/`)

## Privacy note

This repo may contain personal notes and assistant context.
Keep it **private** unless you intentionally clean and review its contents.

## Basic git workflow

From this folder:

```bash
git status
git add -A
git commit -m "Describe what changed"
git push
```

## Open in VS Code

```bash
code /home/nian/.openclaw/workspace
```

## Suggested structure for future work

You can add folders like:
- `projects/` for code projects
- `scripts/` for utilities
- `notes/` for general notes
- `experiments/` for prototypes

## Tracked vs ignored

Ignored by default:
- `.openclaw/`
- common local/editor/build clutter

Review `.gitignore` before adding new tools or project types.
