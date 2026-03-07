# Mykhailo Yarytskyi

Senior backend and full-stack engineer focused on production-style systems, integrations, and operational reliability.

I build API-first services and platform components with clear domain boundaries, predictable workflows, and maintainable delivery pipelines. I focus on systems that are technically solid and product-useful, from design decisions through day-to-day operations.

## Core Engineering Scope

- Backend systems for business-critical workflows, access control, and auditability
- System design and architecture for services with explicit reliability and ownership boundaries
- Integration-heavy services (webhooks, normalization, idempotency, retries, delivery tracking)
- Async and event-driven processing with queues, workers, and replay/recovery flows
- Data and reporting services with SQL-first modeling, recomputation pipelines, and caching
- Operational tooling: health/status models, incident/retry workflows, and operator-facing APIs
- Containerized development and deployment workflows with Docker and Linux

## Technology Focus

**Languages:** PHP, TypeScript/Node.js, Go, Java, SQL, Bash  
**Frameworks:** Laravel, Symfony, NestJS, Express, Spring Boot, React, Next.js  
**Data and Messaging:** PostgreSQL, MySQL, Redis, RabbitMQ  
**Infrastructure and Ops:** Docker, Docker Compose, Linux, Apache/Nginx, CI/CD workflows  
**Delivery:** REST APIs, WebSockets, validation and policy layers, testing and quality gates

## Featured Repositories

### 1) [deal-room-api](https://github.com/mmmihaeel/deal-room-api)
Secure Laravel API for organization-scoped document collaboration with role-aware permissions, expiring share links, and immutable audit events.  
**Why it matters:** demonstrates security-focused backend design (RBAC/policy checks, scoped access, token-hash sharing model, auditable actions).  
**Stack:** PHP, Laravel, MySQL, Redis, Docker.

### 2) [conference-orchestrator](https://github.com/mmmihaeel/conference-orchestrator)
Symfony backend for conference/event operations with participant workflows, lifecycle guardrails, reminders, and signed webhook handling.  
**Why it matters:** demonstrates state-machine-driven domain logic and queue-backed orchestration for operational workflows.  
**Stack:** PHP, Symfony, PostgreSQL, Redis, RabbitMQ, Docker.

### 3) [integration-gateway](https://github.com/mmmihaeel/integration-gateway)
Node.js service for third-party webhook ingestion, canonical event normalization, async processing, retry/replay control, and delivery/audit tracking.  
**Why it matters:** demonstrates practical integration architecture with layered idempotency and reliability controls.  
**Stack:** TypeScript, Node.js (Fastify), PostgreSQL, Redis, RabbitMQ, Docker.

### 4) [realtime-ops-platform](https://github.com/mmmihaeel/realtime-ops-platform)
NestJS microservices backend for operational job processing, alerts/incidents, notifications, and live WebSocket updates.  
**Why it matters:** demonstrates multi-service architecture, queue-driven processing, realtime fanout, and operational state modeling.  
**Stack:** TypeScript, NestJS, PostgreSQL, Redis, RabbitMQ, WebSockets, Docker.

### 5) [pg-analytics-service](https://github.com/mmmihaeel/pg-analytics-service)
Go analytics backend over PostgreSQL with precomputed metric snapshots, manual recomputation workflows, and audit-aware management endpoints.  
**Why it matters:** demonstrates SQL-heavy backend engineering, cache/version invalidation strategy, and controlled recomputation lifecycle design.  
**Stack:** Go, PostgreSQL, Redis, Docker.

### 6) [ops-monitor](https://github.com/mmmihaeel/ops-monitor)
Spring Boot service for monitored-service health, failed-job retries, incident lifecycle, and auditable operator interventions.  
**Why it matters:** demonstrates platform-ops thinking and explicit operational control-plane patterns in Java.  
**Stack:** Java, Spring Boot, PostgreSQL, Redis, Docker.

### 7) [linux-infra-lab](https://github.com/mmmihaeel/linux-infra-lab)
Linux infrastructure lab with Apache reverse proxying, Docker Compose topology, Bash automation, backup/restore runbooks, and diagnostics.  
**Why it matters:** demonstrates practical infrastructure ownership beyond application code.  
**Stack:** Linux, Bash, Apache, Docker Compose, Node.js, PHP, MySQL, PostgreSQL, Redis.

## Selected Professional Work (LinkedIn-backed)

In addition to public repositories, my LinkedIn experience reflects delivery across product, contract, and freelance environments where source code is not always public.

- Built and maintained full-stack platforms combining React/Next.js frontends with Node.js/PHP backend services.
- Delivered API integrations and workflow automation across content, CRM, and business operations use cases.
- Worked with SQL and NoSQL data models, query tuning, caching, and reliability-focused backend refactors.
- Contributed to CI/CD, containerized environments, release workflows, and cloud-oriented service operations.
- Implemented and supported AEM-based enterprise delivery flows, including component systems, dispatcher/cache concerns, and content operations.

## Portfolio Navigation

If you want a fast technical review, start here:

- **Secure backend access and auditability:** [deal-room-api](https://github.com/mmmihaeel/deal-room-api)
- **Lifecycle orchestration and messaging:** [conference-orchestrator](https://github.com/mmmihaeel/conference-orchestrator)
- **Integrations and idempotent event processing:** [integration-gateway](https://github.com/mmmihaeel/integration-gateway)
- **Realtime operational microservices:** [realtime-ops-platform](https://github.com/mmmihaeel/realtime-ops-platform)
- **Data/reporting backend in Go:** [pg-analytics-service](https://github.com/mmmihaeel/pg-analytics-service)
- **Ops control-plane in Java:** [ops-monitor](https://github.com/mmmihaeel/ops-monitor)
- **Linux and infrastructure workflows:** [linux-infra-lab](https://github.com/mmmihaeel/linux-infra-lab)

## Current Focus

- Backend architecture for systems with strong operational requirements
- Reliable async workflows (queues, retries, replay, failure handling)
- Integration boundaries and service-to-service contracts
- Practical infrastructure and operator-facing reliability tooling

## Contact

- GitHub: [github.com/mmmihaeel](https://github.com/mmmihaeel)
- LinkedIn: [linkedin.com/in/mykhailo-yarytskyi-330aa0284](https://www.linkedin.com/in/mykhailo-yarytskyi-330aa0284/)
- Email: [mikael11032005@gmail.com](mailto:mikael11032005@gmail.com)
- Portfolio: [mmmihaeel.webflow.io](https://mmmihaeel.webflow.io/)
