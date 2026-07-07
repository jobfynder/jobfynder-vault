# Jobfynder Vault

Business memory that compounds. Every note is plain markdown, git-tracked, synced everywhere.

## Folders
- `research/` — Market intel, trends, competitors
- `marketing/` — Campaigns, content, strategy
- `product/` — Features, decisions, roadmap
- `daily/` — Day logs (YYYY-MM-DD.md)
- `clients/` — Partner notes
- `meta/` — Vault rules for AI agents
- `templates/` — Starter templates for notes

## Sync Chain
Server writes → git push → GitHub → pull on laptop → Obsidian Sync → mobile

## How Hermes Uses This
The `vault-workflow` skill makes Hermes:
1. Read vault context before answering
2. Save research notes automatically
3. Write daily summaries
4. Run marketing workflows
