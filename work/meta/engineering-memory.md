# Hermes Memory — Persistent Preferences

## Output Formatting
- Always deliver responses in small chunks that fit within output limits
- When content is long, split into numbered parts (Part 1 of N, Part 2 of N, etc.)
- Never let responses get truncated — if it's too long, break it up proactively
- Ask for confirmation between parts before continuing

## Web Dashboard
- URL: https://intel.tailb37ef4.ts.net
- Fixed: Tailscale hostname added to allowed hosts (patched `_LOOPBACK_HOST_VALUES` in web_server.py)
- Referred to as: Hermes web dashboard / web UI / admin web
- Port: 9119 (internal)
- Exposed via Tailscale serve

## Daily Cron
- daily-hermes-tips: 5 Hermes tips every day at 12 PM Eastern (16:00 UTC)
- Delivers to: origin (this Telegram chat)
- Uses direct Gemini provider via system crontab script
- Next run: daily at 16:00 UTC

## Sourcing Bot
- Bot: @jobfynder_sourcing_bot
- Profile: sourcing (/root/.hermes-admin/profiles/sourcing/)
- Gateway service: hermes-sourcing-gateway
- Tools: browser (local Chromium), terminal, file, memory, session_search
- Sourced requirements saved to research/sourced-requirements/
- Browserbase needed for Cloudflare-bypassed scraping on major job boards
