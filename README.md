<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a1aff&height=200&section=header&text=Kallebe%20Gallo&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Engineer%20·%20AI%20Products&descAlignY=58&descSize=22&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6E40C9&center=true&vCenter=true&width=650&lines=I+ship+SaaS+products+to+production;FastAPI+%C2%B7+Next.js+%C2%B7+PostgreSQL+%C2%B7+Docker;Multi-tenant+architecture+%26+row-level+security;Based+in+Ticino%2C+Switzerland+%F0%9F%87%A8%F0%9F%87%AD)](https://git.io/typing-svg)

<a href="https://www.linkedin.com/in/kallebesiqueira" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:kallebesiqueira@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://portafoglio-alpha.vercel.app" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
</a>

</div>

---

## What I actually build

I'm a full stack engineer in **Ticino, Switzerland**, working mostly on **multi-tenant SaaS** — the unglamorous parts included: tenant isolation, migrations, billing webhooks, i18n, CI, and the deploy pipeline.

My main project, **Gallo CRM**, is live in production with paying-tier billing, seven languages and row-level security enforced in PostgreSQL. It isn't a tutorial clone; it's a product with users, a worker queue and a backup job.

**Open to full-time and contract work.**

---

## Featured projects

### ▸ [Gallo CRM](https://github.com/kallebesiqueira-dev/crm_gallo) — multi-tenant CRM in production

A complete CRM for small European sales teams: leads, pipeline, quotes, contracts, invoicing and an AI assistant.

- **Multi-tenancy with PostgreSQL row-level security** — isolation enforced at the database, not in application code
- **7 locales** (EN/DE/FR/IT/RM/PT/ES) with automated key-parity checks in CI — including Romansh, Switzerland's fourth national language
- **Stripe billing** live, with webhook-driven subscription state
- **6 CI workflows** — backend, frontend, e2e (Playwright), Docker, security scan, database backup
- Background worker for PDF generation and outbox-pattern automations

`FastAPI` · `Next.js` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `Redis` · `Stripe` · `Docker` · `Playwright`

**[Live →](https://app.gallo-crm.com/)**

---

### ▸ [EtzahWeb](https://github.com/kallebesiqueira-dev/nuovoetzah) — a trilingual production site with no framework

The site for my web studio, built deliberately with **zero framework and zero backend** — and it still does full internationalisation, SEO, a sitemap and a web manifest.

- A hand-written i18n runtime (IT / PT / EN) — nested-key lookup, a `t()` helper, change subscribers, `localStorage` persistence and an accessible language switcher, driving 1,284 lines of translations. No library
- Deployed from `/docs` on GitHub Pages with a custom domain
- Contact handling without a server

Worth a look if you're curious how much you can ship before reaching for React.

`Vanilla JS` · `CSS3` · `GitHub Pages` · `SEO`

**[Live →](https://www.etzahweb.com)**

---

### ▸ [Inbox AI](https://github.com/kallebesiqueira-dev/Inbox-AI) — AI email automation for B2B back offices

Turns an inbox into structured work: classifies incoming mail, drafts replies and surfaces opportunities.

- TypeScript monorepo, backend and frontend in one CI pipeline
- Playwright end-to-end coverage
- Deployed on Render with a cold-start keepalive workflow

`TypeScript` · `Node.js` · `React` · `Playwright`

**[Live demo →](https://inbox-ai-client-gamma.vercel.app)**

---

### ▸ [Task Manager SaaS](https://github.com/kallebesiqueira-dev/task-manager-saas) — containerised Kanban, documented API

A Trello-style task manager built to practise clean service boundaries rather than to look pretty.

- Separate backend and frontend, orchestrated with `docker compose`
- A written [`API.md`](https://github.com/kallebesiqueira-dev/task-manager-saas/blob/main/API.md) — the endpoints are documented, not guessed
- Prisma schema with migrations

`Next.js` · `Express` · `Prisma` · `Docker` · `TypeScript`

---

### ▸ [Alívio do Professor](https://github.com/kallebesiqueira-dev/alivio-do-professor) — AI grading for Brazilian teachers

A SaaS that grades written assignments so teachers get their evenings back.

- Provider-agnostic LLM layer — OpenAI, Anthropic, Google and Groq behind one interface, so a model can be swapped without touching feature code
- Supabase auth and Postgres with SQL migrations
- PDF parsing pipeline for submitted work

`Next.js` · `TypeScript` · `Supabase` · `PostgreSQL`

---

### ▸ [La Mia Piccola Storia](https://github.com/kallebesiqueira-dev/la-mia-piccola-storia) — animation-heavy storytelling site

Scroll-driven narrative site, multilingual, built to see how far animation can go before performance suffers.

- GSAP for timeline-based scroll sequences, Framer Motion for component transitions
- `i18next` with browser language detection

`React` · `TypeScript` · `GSAP` · `Framer Motion` · `Vite`

**[Live →](https://la-mia-piccola-storia.vercel.app)**

---

## Tools I use in shipped work

Everything listed here appears in a public repository above — no aspirational entries.

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,python,react,nextjs,tailwind&theme=dark" alt="TypeScript, JavaScript, Python, React, Next.js, Tailwind"/>
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,prisma,supabase&theme=dark" alt="Node.js, Express, FastAPI, PostgreSQL, Prisma, Supabase"/>
<br/>
<img src="https://skillicons.dev/icons?i=docker,redis,git,githubactions,vite,vercel&theme=dark" alt="Docker, Redis, Git, GitHub Actions, Vite, Vercel"/>

</div>

**Also working with:** Alembic · SQLAlchemy · Playwright · Stripe · Sentry · PostHog · Cloudflare R2 · Railway

---

## Currently

- Hardening **Gallo CRM** for its public launch — QA, accessibility and performance
- Learning **system design** and cloud infrastructure in more depth
- **Open to opportunities** in Switzerland, Italy, or remote

---

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=kallebesiqueira-dev&theme=tokyonight" height="175em" alt="GitHub stats"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kallebesiqueira-dev&theme=tokyonight" height="175em" alt="Languages"/>

<br/><br/>



<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1aff,100:0d1117&height=120&section=footer" width="100%"/>

</div>
