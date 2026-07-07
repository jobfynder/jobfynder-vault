# Vault Rules for AI Agents

This vault is Jobfynder's business memory. Every AI agent (Hermes, Claude, etc.)
reads and writes here. Follow these rules exactly.

## File Naming
- Use descriptive names: `staffing-market-trends.md` not `note1.md`
- Daily logs: `YYYY-MM-DD.md`
- No dates in research/marketing filenames (keeps them stable)

## First Line
Every file starts with `# Title`. That's the only formatting rule.

## What Goes Where

| Folder | Content |
|--------|---------|
| `research/` | Market intel, competitor analysis, industry trends |
| `marketing/` | Campaigns, content, strategy docs |
| `marketing/brand-os/` | 12-pillar Brand OS framework (00-index + 01-12 numbered pillars) |
| `product/` | Feature decisions, roadmap thinking |
| `daily/` | Day logs with what was done and decided |
| `clients/` | Partner notes (if applicable) |
| `meta/` | This file — vault conventions |
| `templates/` | Starting points for new notes |
| `meta/inbox.md` | Quick capture — ideas, links, rough thoughts to review later |

## Golden Rule
Write notes so a human can read them in 30 seconds and know exactly what matters.
Short paragraphs, bold for key points, no fluff.

## Sync Check
Run `bash /root/.hermes-admin/ops-log/vault-status.sh` anytime to verify all files
are pushed to GitHub.

On mobile (Working Copy): Open app → tap repo → Pull. That's it.
If you see 12 files on GitHub but fewer on mobile → Pull again. Working Copy needs
a manual pull each time.
