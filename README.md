# Fullstack Starter — Go/Fiber + Postgres

Minimal, production-minded starter for a CRUD web app:
- **Backend:** Go + Fiber, REST, migrations
- **Data:** PostgreSQL
- **Ops:** Docker/Compose, GitHub Actions (CI)
- **Docs:** human-first README, OpenAPI (later)

> Goal: show clean structure, repeatable local run, and a sane engineering process.

---

## Tech stack
Go 1.22 • Fiber v2 • PostgreSQL 16 • Docker/Compose • GitHub Actions • Makefile

---

## Quick start
_Local run and Docker will work after the first features are implemented._
```bash
# Local (after init)
go run ./cmd/api

# Docker (after Dockerfile/compose)
docker compose up --build
```
