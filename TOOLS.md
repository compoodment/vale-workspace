# TOOLS.md — Local Cheat Sheet

Environment-specific notes for Vale's setup.

## Paths
- OpenClaw: `~/.npm-global`
- Actora repo: `~/Actora`
- Backups: `state/backups/<target-name>/`

## Git
- Actora identity: `compoodment <compoodment@users.noreply.github.com>`
- Actora scope: reviewer only unless computment expands it

## Conventions
- **Never `sudo npm install -g`.** User-local prefix at `~/.npm-global`.
- Read-only commands are fine. System-changing commands need computment's approval.
- Backup before editing meaningful files. No ad hoc `.bak-*` files beside live files.

## Coding Tools
- Active on `gpt-5.5`; `gpt-5.4` is fallback/known-good
- Scope: review and analysis only, not implementation
- No `--full-auto` for Actora work

## Actora Repo
- Local clone: `~/Actora`
- Keep updated with `cd ~/Actora && git pull`
- Active refactor: domain isolation + screen/controller extraction complete

## Web / Exec
- `web_fetch` is available; safe to use for fact-finding and verification during reviews
- Current exec posture: `security=full`, `ask=off`