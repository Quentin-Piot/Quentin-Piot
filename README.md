# Quentin Piot — Senior Full-Stack Engineer

I build **data-intensive and AI-powered products** with a strong focus on **backend engineering**, **distributed systems**, and **cloud-native architecture**.

My main stack is **Python**, **TypeScript**, and **AWS**, with experience across **FastAPI**, **React/Vue**, **Terraform**, **Docker**, and production-grade **CI/CD**.

I enjoy designing reliable systems end to end, from product interfaces and APIs to infrastructure, observability, and deployment workflows.

---

## Summary

- **Backend:** Python (FastAPI) • TypeScript/Node.js • Rust • PostgreSQL/DynamoDB • Redis • RabbitMQ/SQS • CQRS/DDD
- **Frontend:** React/Next.js • Vue 3 + Pinia • TypeScript
- **Cloud/DevOps:** AWS • Terraform • Docker • GitHub Actions • basic Kubernetes
- **Focus:** distributed systems • AI-powered products • observability • CI/CD • production readiness

---

## What I Build

- **Reliable backends** with clean boundaries, idempotent handlers, retry/backoff strategies, and asynchronous workflows
- **Cloud-native applications** with solid infrastructure, CI/CD, and infrastructure as code
- **Production-ready systems** with observability, health checks, metrics, and actionable monitoring
- **Secure-by-default architectures** using least-privilege access, HTTPS, JWT/OAuth2, and modern deployment practices

---

## Featured Projects

### HPTP — High-Performance Trading Platform

**Goal:** demonstrate end-to-end capability to build a cloud-native, full-stack trading simulation platform for a demanding technical environment.

**Repo:** [high-performance-trading-platform](https://github.com/Quentin-Piot/high-performance-trading-platform)

**Highlights**
- **Backend:** FastAPI service with a Monte Carlo simulation worker, vectorized with NumPy/Pandas; portfolio analytics including P&L, drawdown, and Sharpe ratio
- **AI layer:** RAG-based assistant for contextual documentation access and developer-facing help
- **Architecture:** AWS ECS Fargate (API + worker), ALB, S3 + CloudFront (SPA), RDS PostgreSQL, optional DynamoDB for event logs
- **Auth:** AWS Cognito with Google Sign-In; SPA communicates with the API via JWT, with roles mapped through Cognito groups
- **Frontend:** Vue 3 + Pinia; real-time progress updates for long-running jobs
- **CI/CD:** GitHub Actions for build, type-checking, tests, and Terraform workflows
- **Observability:** CloudWatch metrics and alarms, structured logs, health and readiness endpoints
- **Cost control:** lightweight ECS services, S3/CloudFront caching strategy, lifecycle rules, and reasonable defaults

### Rust Real-World Backend — Production-Ready Axum API

**Goal:** build a type-safe, high-performance REST API with modern Rust practices and a clean backend architecture.

**Repo:** [axum-diesel-real-world](https://github.com/Quentin-Piot/axum-diesel-real-world)

**Highlights**
- **Stack:** Axum • Diesel ORM • PostgreSQL • Deadpool • UUID support
- **Architecture:** Hexagonal/Clean Architecture with DDD principles and clear separation between domain, infrastructure, and handlers
- **Error handling:** idiomatic Rust patterns with proper propagation and explicit conversions
- **Database:** Diesel migrations, Docker Compose setup, health checks, and connection pooling

---

## Other Projects

- **EcoManager (React Native)** — Budget and transactions app with a mobile-first UX focus  
  [Repo](https://github.com/Quentin-Piot/eco-manager)

- **Carbon Impact (React Native)** — Carbon footprint tracking application  
  [Repo](https://github.com/Quentin-Piot/carbon-impact)

---

## Tech Stack

- **Backend:** Python, FastAPI, Node.js, TypeScript, Rust, REST, GraphQL
- **Data:** PostgreSQL, MongoDB, DynamoDB, Redis, RabbitMQ, SQS
- **Cloud/DevOps:** AWS, GCP, Terraform, Docker, GitHub Actions, Kubernetes
- **Frontend:** React, Next.js, Vue, Angular, TypeScript, Vite, Tailwind
- **Testing/Quality:** pytest, vitest, ESLint, Prettier, Biome, Zod, Pydantic, Clippy, rustfmt

---

## Links

- **Portfolio:** [quentinpiot.com](https://quentinpiot.com)
- **LinkedIn:** [linkedin.com/in/quentin-piot](https://linkedin.com/in/quentin-piot)
- **GitHub:** [github.com/Quentin-Piot](https://github.com/Quentin-Piot)
- **Email:** qkpiot@gmail.com
