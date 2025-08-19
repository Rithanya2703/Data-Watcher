# Data Change Watcher (Beginner → E2E)

This project monitors folders/DB tables for changes, records an **audit trail**, and can trigger **downstream jobs**.

## Goals
- Learn by building step-by-step.
- MVP: Watch a folder → record events in database → view them via API.

## Tech (we’ll add gradually)
- Backend: FastAPI, SQLAlchemy
- Background jobs: Celery + Redis
- DB: Postgres
- Watcher: watchdog
- Frontend (later): React (Vite + TS + Tailwind)
- Docker for local dev
- GitHub Actions (later) for CI

## How this tutorial works
I’ll build this with step-by-step instructions. After each step, I’ll verify it’s working before moving on.
