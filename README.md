## Wole Abraham

Backend-leaning full-stack engineer. Computer Science graduate and ALX Software
Engineering alumnus. I build operational systems for organisations that run on
field data — construction reporting, land administration, scheduling and
service platforms — and increasingly, applications with language models wired
into the core rather than bolted on the side.

Most of my work is production software with real users behind it: a construction
fleet and progress reporting platform feeding Power BI, a land documentation
portal handling statutory applications, a concierge platform with client and
admin surfaces, and a voice-driven clinic scheduler.

---

### What I work with

**Languages** — Python, TypeScript, JavaScript, SQL

**Backend** — FastAPI, Django, Flask, Node.js/Express, SQLAlchemy, Prisma,
SQLModel

**Frontend** — Next.js (App Router), React, React Native/Expo, Tailwind,
shadcn/ui

**Data** — PostgreSQL, Supabase, SQLite, Redis, pandas, scikit-learn

**Infrastructure** — Vercel, Render, Railway, Ubuntu VPS (Gunicorn + Nginx),
GitHub Actions, Cloudflare R2 and S3-compatible storage, Docker

**AI** — Anthropic Claude, OpenRouter, retrieval and prompt-driven generation
against domain corpora

---

### Selected work

**[hitech-portal](https://github.com/wole-abraham/hitech-portal)** — Field
operations platform for a construction company. Workers submit daily progress
reports against chainage references with photo and video attachments; office
staff manage workforce, equipment and planned activities. Includes a dedicated
Power BI feed serving flattened datasets to external reporting.
*Next.js, TypeScript, Supabase, Cloudflare R2, Vitest.*

**[ipms-backend](https://github.com/wole-abraham/ipms-backend)** — Property
management API with machine learning for rent estimation and tenant risk
scoring. Runs on SQLite locally and switches to PostgreSQL in deployment.
*FastAPI, SQLAlchemy, scikit-learn.*

**[reflect](https://github.com/wole-abraham/reflect)** and
**[reflect-mobile](https://github.com/wole-abraham/reflect-mobile)** — A daily
reflection tool that generates writing in the user's own voice from a corpus of
their past work, then publishes on approval. Web app plus an Expo companion
client sharing one backend, with bearer-token auth layered over cookie sessions
for mobile.
*Next.js, Expo/React Native, Anthropic Claude, Supabase Vault.*

**[speed-work-bro](https://github.com/wole-abraham/speed-work-bro)** — Clinic
appointment system with two front doors: a voice agent that books over the
phone, and a web UI. Learns each patient's booking habits to suggest slots, and
predicts no-show risk to allow capacity-aware overbooking.
*FastAPI, Vapi, Supabase.*

**[LandsBackend](https://github.com/wole-abraham/LandsBackend)** and
**[landsportal](https://github.com/wole-abraham/landsportal)** — Land
documentation and title services portal. Applicants submit searches, consent,
certified true copies and regularization requests with supporting documents;
staff process them and issue invoices through an admin surface.
*FastAPI, Supabase, S3-compatible storage.*

**[Miora concierge platform](https://github.com/wole-abraham/concierge-backend)**
— Bespoke concierge service with client and admin surfaces, JWKS-verified
Supabase auth cached in Redis, and generated invoices delivered as email-safe
HTML. Live at [miora.devwole.space](https://miora.devwole.space).
*FastAPI, Supabase, Redis, Resend.*

**[DeDoc](https://github.com/wole-abraham/DeDoc)** — A first-order logic expert
system for medical diagnosis. Forward chaining derives facts from reported
symptoms; backward chaining selects the most informative next question. Every
conclusion is traceable to the rule that produced it, with no statistical model
involved.
*Python, FastAPI.*

---

### Background

Previously interned at the **Lagos State Land Administration e-GIS Portal**,
working on data collection across projects — which is where the land
administration and geospatial reporting thread in my work started.

I am comfortable owning a system end to end: schema design, API, deployment,
and the operational scripts that keep data flowing into it.

---

### Contact

- Email — [wole1702@gmail.com](mailto:wole1702@gmail.com)
- GitHub — [@wole-abraham](https://github.com/wole-abraham)

Open to collaboration and interesting backend or full-stack problems.
