# Contributing to TalentSense

Thanks for your interest in contributing!

TalentSense is a small, fast-moving project. The goal is to keep changes clear, reviewable, and aligned with the MVP.

---

## Ways to contribute

- Report bugs (use the Bug Report template)
- Propose improvements (use the Feature Request template)
- Submit pull requests for well-scoped changes

If you're unsure where to start, open an issue and describe the problem you want to solve.

---

## Project structure

- `talentsense-frontend` — React + TypeScript (Vite)
- `talentsense-backend` — FastAPI (Python) + PostgreSQL
- `talentsense-infra` — Docker, CI/CD notes, and docs
- `.github` — org-level templates and policies

---

## Ground rules

- Keep PRs **small and focused** (one change, one purpose)
- Prefer clarity over cleverness
- Avoid introducing new dependencies unless clearly justified
- Do not commit secrets (API keys, tokens, credentials)

---

## Development workflow

### Branching

- Default branch: `main`
- Create feature branches from `main`:
  - `feature/<area>-<short-slug>`
  - Examples:
    - `feature/frontend-evaluate-form`
    - `feature/backend-evaluations-endpoint`
    - `feature/infra-docker-compose`

### Commits

Use clear, imperative messages:

- `Add evaluation result schema`
- `Fix validation error on CV upload`
- `Refactor OpenAI response parsing`

### Pull requests

Open a PR early if you want feedback, but keep it scoped.

Each PR should include:

- **What changed** and **why**
- How to test locally (or what was validated)
- Any follow-ups (out of scope for this PR)

---

## Coding standards (high-level)

We keep standards lightweight but consistent:

- Prefer strict typing/validation where applicable
- Keep API contracts explicit (request/response schemas)
- Validate and sanitize all LLM outputs before persistence
- Add minimal tests for business-critical logic when possible

---

## Issue tracking

We use **GitHub Projects** for status, area, and priority tracking.
Issues should contain enough detail to be actionable (repro steps for bugs, acceptance criteria for features).

---

## Security

Please do not report vulnerabilities via public issues.
See `SECURITY.md` for responsible disclosure instructions.

---

## License

By contributing, you agree that your contributions will be licensed under the project’s license.
