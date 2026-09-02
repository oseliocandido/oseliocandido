# Oselio Candido

**Backend & data engineer building reliable SaaS systems and data platforms — increasingly with AI agents as part of the toolchain.**

I work across the stack from PostgreSQL schema design up through FastAPI services to production CI/CD. I care more about correctness, explicit boundaries, and systems that fail predictably than about chasing frameworks.

## What I Build

- **Backend APIs & services** — async FastAPI services backed by SQLAlchemy/asyncpg, structured around domain-driven layering (domain → application → infrastructure → presentation)
- **SaaS products** — a fiscal-data analytics platform (SAF-T processing for Portuguese SMBs) and an ERP-style operations system, both spec-driven from PRD to implementation
- **Data pipelines** — dbt + PostgreSQL pipelines on AWS, BigQuery utilities, ETL packaging
- **Quality & CI/CD infrastructure** — enforced coverage/complexity/lint gates wired into layered GitHub Actions pipelines (unit, integration, security, quality)
- **Agentic development workflows** — custom agent specs, prompts, and instruction files that make AI-assisted development repeatable rather than ad hoc

## Engineering Interests

Data modeling · async I/O and connection pooling · database correctness · API design · authentication & authorization · CI/CD quality gates · spec-driven development · agentic engineering workflows

## Technology Stack

**Backend**
Python · FastAPI · async SQLAlchemy · asyncpg · Alembic · Pydantic

**Data**
SQL · PostgreSQL · dbt · BigQuery · Databricks · ETL/ELT pipelines

**Infrastructure**
Docker · Docker Compose · Nginx · Linux · Redis · GitHub Actions (CI/CD)

**Frontend**
TypeScript · React

**AI / Agents**
LLM-assisted development · agent/prompt specification · spec-driven workflows

**Engineering practice**
Git · automated quality gates (coverage, mypy, ruff, radon) · testing (pytest, unit + integration) · security-scanned CI pipelines

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

## Engineering Philosophy

- Model the domain before choosing abstractions.
- Prefer explicit boundaries over implicit magic.
- Treat the database as part of the correctness model, not an afterthought.
- Automate the parts of engineering that don't require judgment — quality gates, not code review.
- Use specifications (PRDs, agent instructions) to reduce ambiguity before writing code.
- Use AI agents as engineering tools with enforced guardrails, not as a replacement for engineering judgment.
- Prefer a simple architecture until complexity is actually justified.

## Current Focus

Backend/SaaS architecture for two products in active development, tightening CI quality gates, and building out spec-driven, agent-assisted development workflows.

## Selected Projects

**SaaS fiscal analytics platform** (private)
A SAF-T (Portuguese fiscal XML) analytics product — parses ERP-generated fiscal documents into sales, product, and customer intelligence. Async FastAPI + SQLAlchemy + asyncpg backend, React/TypeScript frontend, built spec-first from a PRD with dedicated agent/prompt instructions for feature implementation, testing, and refactoring.

**Bakery ERP** (private)
A modular-monolith ERP backend (auth, inventory, financial, RH modules) built with strict DDD layering and enforced quality gates — coverage thresholds, complexity limits, zero-warning lint/type checks — driving a layered CI/CD pipeline (unit, integration, security, quality) via reusable GitHub Actions workflows. 2FA auth, Redis-backed sessions.

**[sales-pipeline](https://github.com/oseliocandido/sales-pipeline)**
A dbt + PostgreSQL sales data pipeline on AWS, with data quality validation via Pydantic and docs generated with MkDocs.

**[big-query-backup-util](https://github.com/oseliocandido/big-query-backup-util)**
A Dockerized utility for backing up BigQuery datasets.

## Contact

[LinkedIn](https://linkedin.com/in/oseliocandido) — open to conversations about backend architecture, data platforms, or agentic development workflows.
