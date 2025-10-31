# Quentin Piot — Full-Stack & Cloud Engineer 

---

## Summary

- **Backend:** FastAPI / Python • Node.js / TypeScript • Event-driven (SQS) • PostgreSQL/DynamoDB • Redis • CQRS/DDD
- **Cloud/DevOps:** AWS (ECS Fargate, ALB, CloudFront, Cognito, S3, RDS, DynamoDB, SQS, CloudWatch) • Terraform • GitHub Actions • Docker • basic K8s
- **Frontend:** Vue 3 + Pinia • React/Next.js • OAuth2/JWT/Cognito
- **Practices:** CI/CD, trunk-based, automated testing, IaC, metrics & tracing, security by default
- **Availability:** **January 2026** • Paris (remote/hybrid OK)
- **Certifications:** Preparing **AWS Solutions Architect Associate** & **Terraform Associate** (in progress)

---

## What I Ship

- **Production-ready backends** with clean boundaries (Hexagonal/DDD), idempotent handlers, retry/backoff, and dead-letter strategies.
- **Observability first:** structured logs, metrics (p95 latency, error budgets), health checks, and actionable dashboards.
- **CI/CD that protects quality:** build → test → scan → deploy gates, infra drift detection, preview environments.
- **Security basics baked-in:** least privilege IAM, HTTPS everywhere at the edge, JWT/Cognito auth, secret rotation via GitHub OIDC + AWS.

---

## Featured Project — HPTP (High-Performance Trading Platform)

**Goal:** demonstrate end-to-end capability to build a **low-friction, cloud-native, full-stack trading simulation platform** suitable for a quant environment.

**Repo:** https://github.com/Quentin-Piot/high-performance-trading-platform

**Highlights**
- **Backend:** FastAPI service with a Monte-Carlo simulation worker, vectorized with NumPy/Pandas; P&L, drawdown, Sharpe.
- **Architecture:** AWS ECS Fargate (API + worker), ALB, S3 + CloudFront (SPA), RDS PostgreSQL, optional DynamoDB for event logs.
- **Auth:** AWS Cognito with Google Sign-In; SPA talks to API via JWT (RS256), roles mapped via Cognito groups.
- **Frontend:** Vue 3 + Pinia; WebSocket progress feed (live job progress and ETA).
- **CI/CD:** GitHub Actions (build, type-check, tests, IaC plan/apply, invalidations); Terraform for all infra (OAI, OAC, cache policies).
- **Observability:** CloudWatch metrics/alarms; structured JSON logs; health and readiness endpoints.
- **Cost control:** small ECS services, S3/CloudFront caching strategy, lifecycle rules, reasonable defaults (no idle GPU waste).
  
---

## Selected Architecture Patterns I Use

- **Domain-centric design:** DDD aggregates, CQRS for read/write separation where it pays off.
- **Event-driven workflows:** SQS with visibility timeouts, poison queues, and idempotency keys.
- **Resilient HTTP:** retry with jitter, circuit breakers, timeouts; clear failure modes.
- **Caching at the edge:** CloudFront cache policies & OAC; SPA routing with fallback; versioned assets.
- **Zero-trust-ish defaults:** private subnets for compute, least-privilege IAM, no public RDS, WAF when exposed.

---

## Tech Stack (Core & Comfort)

- **Backend:** Python (FastAPI), Node.js (NestJS/Express), GraphQL/REST, async IO, NumPy/Pandas
- **Data/Infra:** PostgreSQL, DynamoDB, Redis, RabbitMQ/SQS
- **Cloud/DevOps:** AWS (ECS, ALB, CloudFront, S3, Cognito, RDS, DynamoDB, SQS, CloudWatch), Terraform, GitHub Actions, Docker
- **Frontend:** Vue 3 + Pinia, React/Next.js, TypeScript, Vite, Tailwind
- **Testing/Quality:** pytest, vitest, tsc strict, ESLint/Prettier, schema validation (zod/pydantic)

---

## Github stats

<div align="center">

| GitHub Stats | Favorite Languages |
|--------------|--------------------|
| ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=quentin-piot&show_icons=true&theme=dark&count_private=true&hide_rank=true) | ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=quentin-piot&show_icons=true&theme=dark&layout=compact&langs_count=6&exclude_repo=portfolio-nextjs&hide=html,css,scss) |

</div>

---

## Projects (Selection)

- **High-Performance Trading Platform (HPTP)** — *Cloud-native trading sim with live progress*  
  https://github.com/Quentin-Piot/high-performance-trading-platform

- **Axum Real-World Template (Rust)** — *Scalable backend template with Diesel, DDD structure*  
  https://github.com/Quentin-Piot/axum-diesel-real-world

- **EcoManager (React Native)** — *Budget & transactions, mobile UX focus*  
  https://github.com/Quentin-Piot/eco-manager

- **BioPrisme (production site)** — *OCR + AI over medical PDFs, HDS hosting & encryption*  
  https://bioprisme.com

---

## Experience (Recent)

**Lead Freelance Developer — MAGNETA S.A.S (2024)**  
- Built IoT backend for connected devices; secure B2B API (GraphQL); React admin console.  
- CI/CD, containerization, AWS deployment; monitoring & access control.

**Full-Stack Engineer — Partoo (2022–2024)**  
- Click & Collect backend with Clean Architecture; **CQRS/DDD** in a high-throughput environment.  
- Vue/Nuxt + GraphQL frontend integration; async processing with RabbitMQ/Redis.

---

## How I Work

- **Code that explains itself:** clear boundaries, invariants, and ADRs for non-obvious decisions.
- **Measure, then optimize:** profiling first, then vectorization/async/batch.  
- **Automate ruthlessly:** repeatable environments via IaC, one-click deployments, reproducible jobs.  
- **Documentation kept current:** runbooks, health checks, and diagrams in the repo.

---

## Quick Links

- **HPTP**: https://github.com/Quentin-Piot/high-performance-trading-platform  
- **Portfolio**: https://quentinpiot.com  
- **LinkedIn**: https://linkedin.com/in/quentin-piot  
- **Email**: qkpiot@gmail.com

