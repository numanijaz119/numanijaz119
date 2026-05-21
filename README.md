# Numan Ijaz

**Django & AI Backend Engineer** — I build the backend layer that makes 
AI features work in production: LLM pipelines, multi-tenant SaaS, 
real-time APIs, and Stripe systems.

3+ years · 15+ production SaaS products shipped · Lahore, Pakistan 🇵🇰 · Remote

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/numanijaz09/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:minibhai009@gmail.com)

---

## About

I specialize in the infrastructure layers that most SaaS products need 
but are rarely straightforward to build: multi-tenant architectures, 
LLM integration pipelines with proper caching and structured outputs, 
real-time WebSocket systems, and Stripe subscription engines enforced 
at the API level.

I've shipped production systems across fintech, agricultural trading, 
fitness/coaching, and geospatial verticals. I care about what breaks 
in production — not just what works in dev.

---

## Core Stack

**Backend** — `Python` `Django` `Django REST Framework` `PostgreSQL` 
`PostGIS` `Redis` `Celery` `WebSockets`

**Frontend** — `React` `Next.js` `TypeScript` `Tailwind CSS`

**Mobile** — `React Native` (Expo · iOS & Android)

**AI / LLM** — `OpenAI GPT-4` `Anthropic Claude` `Prompt Engineering` 
`Structured Outputs` `RAG`

**Cloud & DevOps** — `AWS (EC2, S3, RDS)` `Docker` `Nginx` 
`CI/CD` `Vercel` `DigitalOcean`

**Payments** — `Stripe (Subscriptions · Webhooks · Connect)`

---

## Selected Projects

### [Mappex](https://github.com/numanijaz119/...) — Real-Time Geospatial Collaboration
*Django · PostGIS · React Native · Mapbox · Stripe · OpenAI*

Geospatial SaaS where teams create map projects, place markers, and 
collaborate in real time. Built the full platform solo.

- PostGIS point-in-polygon marker validation with **<100ms render time 
  on 500+ pins**
- QR-code onboarding via UUID invite tokens → deep link → instant map 
  access, reducing onboarding friction **75% vs. email invite flows**
- Tiered Stripe subscription engine (Free / $20 / $200/mo) enforced at 
  the **API level on every resource creation call** — not just the 
  frontend — with full webhook lifecycle handling
- GPT-4 analysis pipeline aggregating markers, comments, and geographic 
  data into a structured prompt; results cached in a `ProjectAIAnalysis` 
  model, cutting project review time **~50%**
- Solved N+1 on unlimited-depth nested comment trees using 
  `select_related` / `prefetch_related` and database-level reaction 
  aggregation

---

### [Hectar Labs](https://hectar.global/) — Commodity Trading Platform
*Django · Next.js 15 · TypeScript · Celery · Redis · Pandas · Gemini*

Full trade lifecycle management for agricultural commodity traders.

- P&L automation and shipment tracking across **189+ global ports**
- AI-driven arbitrage detection pipeline over **97,000+ shipment records**
- Async data processing via Celery with Redis; heavy Pandas workloads 
  for trade analytics

---

### [Foxing Fit](https://github.com/numanijaz119/...) — Coach-Driven Workout Audio Generator
*Django · DRF · React · MySQL · Pydub*

SaaS platform for fitness coaches to encode their training methodology 
and generate fully personalized, on-brand workout audio sessions.

- Deterministic template engine — no LLM involved — encoding coach's 
  exact exercise sequencing, round triggers, and sport-specific 
  progressions
- Audio merge engine with **per-segment volume normalization 
  (−20 dBFS target)**, clipping detection, and 192kbps MP3 export
- Diagnosed and fixed a **silent production audio streaming failure** 
  caused by missing `Range` headers in CORS config — a bug that doesn't 
  surface in Django's dev server
- Multi-language support (Dutch + English) at the data model level, 
  designed to scale without schema changes

---

### [Hural.pro](https://github.com/numanijaz119/...) — AI-Powered Resume Screening System
*Django · Vue.js · Microsoft Graph API · Gmail API · OAuth2 · OpenAI*

Replaced a fully manual candidate screening process with an automated 
pipeline.

- Full OAuth2 flows for both Gmail and Microsoft Outlook — token 
  issuance, refresh, and secure storage across both providers
- Automated resume import from email attachments via Microsoft Graph API 
  and Gmail API, fed into an OpenAI extraction and ranking pipeline

---

## Writing & Case Studies
 
> I write about real production problems — not tutorials.
 
- **[How I Built Mappex: A Real-Time Geographic Collaboration Platform — Full-Stack Case Study](https://almondine-aluminum-52e.notion.site/How-I-Built-Mappex-A-Real-Time-Geographic-Collaboration-Platform-Full-Stack-Case-Study-3276ca52b57f807f8742c1c3edf393dd)**
- **[Foxing Fit: Coach-Driven Workout Script & Audio Generator](https://almondine-aluminum-52e.notion.site/Foxing-Fit-Coach-Driven-Workout-Script-Audio-Generator-3256ca52b57f801d95e6d7d6f0fbc33f)**

---

## Let's Work Together

I'm open to **remote contract work and full-time roles** — particularly 
with startups that need backend-heavy AI integration done properly.

If you're building something with LLM pipelines, SaaS infrastructure, 
or real-time systems, reach out:

📧 [minibhai009@gmail.com](mailto:minibhai009@gmail.com) · 
💼 [linkedin.com/in/numanijaz09](https://www.linkedin.com/in/numanijaz09/)
