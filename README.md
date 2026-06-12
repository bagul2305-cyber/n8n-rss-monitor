# HN RSS MONITOR
Automated Hacker News feed monitor built with n8n.
## What it does 
polls the Hacker News RSS feed on  a schedule.
Filters posts by keywords: AI, Startup.
Posts matching articles to a Discord channel automatically.

## Nodes
Schedule Trigger 
RSS read
Filter
HTTP Request (Discord Webhook)

## Stack 
- n8n (self-hosted, local)
- Hacker News RSS
- Discord Webhook
