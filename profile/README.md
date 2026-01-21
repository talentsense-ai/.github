# TalentSense

**TalentSense** is an AI-powered recruiting assistant that compares a candidate’s CV against a Job Description and returns a clear, actionable evaluation: an overall match score, skill breakdown, strengths, risks, and suggested interview questions.

> Built as a small, end-to-end SaaS: modern UI, clean API contracts, persisted history, and cloud-ready deployment.

---

## What it does

Given a **Job Description** and a **Candidate CV**, TalentSense generates:

- **Overall Match Score (0–100)**
- **Skills breakdown** (scored per skill, visualized)
- **Strengths** (what stands out)
- **Risks / gaps** (what to validate)
- **Suggested interview questions** (targeted, practical)

The goal is speed + consistency: **evaluate candidates in seconds**, with outputs you can act on.

---

## MVP experience

Core screens:

- **Evaluate Candidate** — input JD + CV and generate an evaluation
- **Results** — score + skills chart + structured insights
- **History** — list previous evaluations
- **Evaluation Detail** — deep dive into a single evaluation

---

## Repositories

- **talentsense-frontend** — React + TypeScript (Vite), Tailwind, shadcn/ui
- **talentsense-backend** — FastAPI (Python), Pydantic validation, PostgreSQL persistence
- **talentsense-infra** — local dev environment (Docker), CI/CD notes, deployment scaffolding
- **.github** — org profile, templates, and community health files

---

## Tech stack

**Frontend**

- React + TypeScript + Vite
- TailwindCSS + shadcn/ui
- TanStack Query
- React Hook Form + Zod
- Recharts

**Backend**

- Python 3.11+ + FastAPI
- Pydantic (strict validation)
- SQLAlchemy / SQLModel
- PostgreSQL
- OpenAI API (structured JSON outputs)

**Infra**

- Docker + Docker Compose (local dev)
- GitHub Actions (CI)
- Deploy targets: Vercel (frontend) + container PaaS (backend) + managed Postgres

---

## Principles

- **Clear API contracts** between frontend and backend
- **Structured LLM output** (JSON), validated before persistence
- **Simple architecture** (no microservices for MVP)
- **Product-first UI**: clean layout, sensible loading/error states, useful visuals

---

## Roadmap (high-level)

**MVP**

- Evaluate → Results → History → Detail
- Persist evaluations in PostgreSQL
- Cloud deploy + “demo-ready” UI

**V2**

- Auth (multi-user)
- Job templates
- Export (PDF)

**V3**

- Candidate comparisons
- Analytics dashboard
- Optional async processing for evaluations

---

## Contributing

This is an early-stage project. If you want to contribute:

- Open an issue with a clear description (expected behavior, current behavior, screenshots if applicable).
- Keep PRs small and focused.
- Prefer clarity over cleverness.

---

## Status

🚧 In active development — building the MVP end-to-end.
