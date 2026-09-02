# Oselio Candido

**Backend & data engineer building reliable SaaS systems and data platforms — increasingly with AI agents as part of the toolchain.**

I work across the stack from PostgreSQL schema design up through FastAPI services to production CI/CD. I care more about correctness, explicit boundaries, and systems that fail predictably than about chasing frameworks.

## What I Build

- **Backend APIs & services** — async FastAPI services backed by SQLAlchemy/asyncpg, structured around domain-driven layering (domain → application → infrastructure → presentation)
- **SaaS products** — currently a multi-tenant booking/scheduling platform, with tenant isolation enforced at the application layer
- **Data pipelines** — dbt + PostgreSQL pipelines on AWS
- **Quality & CI/CD infrastructure** — enforced coverage/complexity/lint gates wired into layered GitHub Actions pipelines (unit, integration, security, quality)

## Engineering Interests

Data modeling · API design · authentication & authorization · CI/CD quality gates · pragmatic, tool-assisted engineering

## Technology Stack

**Backend:** Python · FastAPI · async SQLAlchemy · asyncpg · Alembic · Pydantic

**Data:** SQL · PostgreSQL · dbt · Databricks · ETL/ELT pipelines

**Infrastructure:** Docker · Docker Compose · Nginx · Linux · Redis · AWS S3 · GitHub Actions (CI/CD)

**Frontend:** TypeScript · React

**Engineering practice:** Git · automated quality gates (coverage, mypy, ruff, radon) · testing (pytest, unit + integration) · security-scanned CI pipelines

<div>
    <img src="./logos/python.png" alt="python" height="32" width="32">
    <img src="./logos/fastapi.svg" alt="fastapi" height="32" width="32">
    <img src="./logos/sqlalchemy.svg" alt="sqlalchemy" height="32" width="32">
    <img src="./logos/postgresql.png" alt="postgresql" height="32" width="32">
    <img src="./logos/redis.svg" alt="redis" height="32" width="32">
    <img src="./logos/docker.png" alt="docker" height="32" width="32">
    <img src="./logos/typescript.svg" alt="typescript" height="32" width="32">
    <img src="./logos/dbt.png" alt="dbt" height="32" width="80">
    <img src="./logos/aws.png" alt="aws" height="32" width="32">
    <img src="./logos/linux.png" alt="linux" height="32" width="32">
</div>

## Agentic Development

I use Claude Code as my primary development tool — its native harness (hooks, skills, custom agents) rather than a heavier SDK-based agent framework. I've moved off GitHub Copilot entirely; Claude Code is what I use day to day now. I've also built with the OpenAI Agents SDK before, but for my own projects I stick to simplicity: plain markdown + frontmatter for agents and skills solves the problem without extra orchestration layers. I write PRDs to scope work, but don't follow formal spec-driven development — the spec informs the build, it doesn't drive a rigid process.

## Engineering Philosophy

- Model the domain before choosing abstractions.
- Prefer explicit boundaries over implicit magic.
- Treat the database as part of the correctness model, not an afterthought.
- Automate the parts of engineering that don't require judgment — quality gates, not code review.
- Use AI agents as engineering tools with enforced guardrails, not as a replacement for engineering judgment.
- Prefer a simple architecture until complexity is actually justified.

## Current Focus

Building a multi-tenant booking/scheduling SaaS end to end — backend, frontend, and infrastructure — while refining how I use Claude Code's agent tooling in day-to-day development.

## Contact

[LinkedIn](https://linkedin.com/in/oseliocandido) · Blog: coming soon
