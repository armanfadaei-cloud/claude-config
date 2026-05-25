# Claude Code Config

This folder holds configuration and memory for [Claude Code](https://claude.ai/code).

## What's tracked

| File/Folder | Purpose |
|---|---|
| `.claude/settings.local.json` | Ignored — machine-specific permissions |
| `memory/` | Persistent memory files Claude writes across sessions |

## What's gitignored

- `sessions/` — ephemeral session state
- `projects/` — per-project conversation history
- `backups/` — auto-generated config backups
- `shell-snapshots/` — shell environment snapshots
