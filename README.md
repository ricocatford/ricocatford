# Ricardo Albarenque

**Full-Stack Developer** · TypeScript · React · Next.js · Node.js · NestJS · LLM integration

I build and ship production web applications end to end, from the database schema and APIs to the UI and the server they run on. At Agencia EGOS I built and deployed two AI-powered SaaS platforms, built a web directory from scratch, and migrated and maintained client websites. I've been training and building my own projects since 2022.

📍 Gijón, Spain · [LinkedIn](https://linkedin.com/in/ricardo-albarenque) · rico.albarenque@gmail.com

---

## Experience

### Developer · Agencia EGOS (Gijón) · May 2026 – Oct 2026

**[AutoSEO](https://autoseo.ricoalb.com)**: multi-tenant platform that generates SEO content with AI
- Built the full Next.js frontend from Figma designs and the NestJS backend (DDD modules, JWT with refresh tokens, roles, per-organization data isolation).
- Automated the content pipeline: a scheduler generates articles with Gemini, publishes them as drafts on the client's WordPress and queues them for human review, with retries and a fallback model.
- Encrypted credentials at rest (AES-256-GCM) and replaced polling with Server-Sent Events.

**[Zapp](https://zapp.ricoalb.com)**: customer-support SaaS built on Meta's WhatsApp Cloud API
- Monorepo with pnpm and Turborepo (Next.js 16, Fastify 5, Prisma 7). Signed Meta webhooks feed BullMQ/Redis queues for inbound messages, outbound messages and status updates.
- AI case classification, voice-note transcription and automatic task and lead creation in the client's CRM.
- Multi-account roles, Meta message templates, Embedded Signup with encrypted tokens, usage quotas and alerts for unanswered conversations.

**mejoresclinicasdentales.com**: directory of dental clinics in Spain
- Built the site almost entirely from scratch.
- Adapted an existing scraper to run across multiple sessions, collecting data on up to 18,000 dental clinics.

**Client websites and support**
- Migrated 14+ client websites in a few weeks and fixed the email, account and site issues that followed.
- Fixed and cleaned up client sites on WordPress, WooCommerce and PrestaShop.

**Infrastructure and deployment**
- Deployed AutoSEO and Zapp to production on an Ubuntu VPS with Docker Compose and Caddy (automatic HTTPS), with isolated networks, non-root containers, UFW and fail2ban.
- Designed layered AI cost controls: per-IP rate limiting, daily quotas per organization, an LLM budget and a kill switch.

---

## Tech stack

| Area | Tools |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, PHP, HTML, CSS |
| Frontend | React, Next.js, Tailwind CSS, Shadcn/UI, Zustand, SWR, React Hook Form, Zod, Bootstrap |
| Backend | Node.js, NestJS, Fastify, Express, Django, Flask, REST APIs, JWT, webhooks |
| Databases & queues | PostgreSQL, MySQL, MongoDB, Prisma, Redis, BullMQ |
| AI | LLM integration (Google Gemini), prompt design, cost and usage limits |
| CMS & e-commerce | WordPress (REST API), WooCommerce, PrestaShop, website migrations |
| DevOps | Docker, Docker Compose, Caddy, Linux (Ubuntu VPS), UFW, fail2ban, AWS S3 |
| Tooling & testing | Git, GitHub, pnpm, Turborepo, Jest, Vitest, Postman, Swagger, Figma |
| Methodologies | Agile (Scrum), Conventional Commits, pull requests |

---

## Personal project

**[Pulseflow](https://github.com/ricocatford/pulseflow)**: AI-native web monitoring engine
`Next.js` `TypeScript` `Tailwind CSS` `Shadcn/UI` `Supabase` `Prisma` `Inngest` `Gemini`
- Built a modular multi-source scraping system (Reddit, Hacker News, RSS, HTML) with rate limiting, robots.txt compliance and exponential-backoff retries.
- Integrated Gemini to summarize content and send change alerts by email and webhook, using Inngest background jobs and a dashboard built with React Server Components.

---

## Education

- **Certificado de Profesionalidad Nivel 3 in Web Application Development**, Dicampus, Nov 2025 – May 2026
- **Level 5 Diploma in Full-Stack Web Development** (equivalent to Spain's FP de Grado Superior), City of Bristol College, 2022–2023, graduated with Distinction

## Languages

Spanish (native) · English (C1)

---

Open to full-stack and backend roles in Spain or remote. If you're hiring, [get in touch](mailto:rico.albarenque@gmail.com).
