# Davi Hoffmann

**AI automation & business operations. I build systems that keep working when nobody is looking.**

São Paulo, Brazil (UTC-3) · [LinkedIn](https://www.linkedin.com/in/davi-hoffmann-ab964917b) · davikh@gmail.com

I spent nine years co-founding and running businesses (fast food, food manufacturing, DTC cosmetics). For the last three I've been designing and shipping AI automations: content machines, multi-agent pipelines, lead flows. I own the architecture, build with AI coding tools in Python and Node, wire the APIs, review every integration, and measure cost per unit. Everything here ran in production for a real business, mine or a client's.

## Featured

| Repository | What it is | Stack | Result |
|---|---|---|---|
| [content-machine](https://github.com/davikh92/content-machine) | Generates, renders and publishes 3 AI videos/week + 3 stories/day for a consumer app, with zero manual steps | Node, GitHub Actions, Gemini (Veo/Omni), Puppeteer, ffmpeg, Cloudinary, Instagram Graph API, Pinterest API, Supabase | 65 reels/quarter at R$ 5.90 (~US$ 1) each |
| [linkedin-editorial-pipeline](https://github.com/davikh92/linkedin-editorial-pipeline) | Seven-agent editorial system: topic research, writing, automated critique, image, publishing, metrics, advisor | Python, Claude API, Gemini, LinkedIn API, Pillow, GitHub Actions | 4 posts/week unattended for 6 months; documented silent-failure post-mortem |
| [lead-prospecting-engine](https://github.com/davikh92/lead-prospecting-engine) | Mine targets with pain signals, one-page diagnosis per target with Claude, PDF, markdown CRM, reply drafts approved on Telegram | Python, Google Places API, Claude API, Puppeteer, Flask, Telegram Bot API | Zero generic messages by design; free-tier mining |
| [n8n-flows](https://github.com/davikh92/n8n-flows) | Lead → enrichment → Claude dossier → Notion → follow-up; keyword comment → DM with dedupe | n8n, Claude API, Notion, Gmail, Instagram Graph API, Google Sheets | Importable JSON + walkthrough videos |

Each README has the problem, an architecture diagram, how to run it, the decisions and trade-offs, and what I'd do differently.

## How I work

- Start before the tool: understand the process, then build the smallest system that fixes it.
- Make it run alone: cron, retries, health checks that e-mail only when action is needed.
- Measure what the business cares about, not vanity metrics. Count generations, not posts.
- Document decisions. Every project here has a `DECISIONS.md` or an equivalent section.
- No secrets in code. Everything reads from environment variables; `.env.example` shows the shape.

## Also

Tem na Semana (meal-planning app I founded) · GTM playbooks for B2B SaaS · AI video for brands (Swift/JBS) · Portuguese · English · Spanish
