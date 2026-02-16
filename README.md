# Andrew Adu — Backend Engineer · DevOps/SRE · Data Systems

Fintech & distributed systems • High-throughput APIs • Secure, observable services





---

## What I do

I build and run backend systems where correctness, uptime, and auditability matter.

- **Backend + databases:** PostgreSQL (incl. PostGIS), MSSQL, MySQL, Redis, MongoDB
- **Reliability mindset:** logs/metrics/traces, incident playbooks, least-privilege access, audit trails
- **Delivery:** CI/CD with GitHub Actions, Dockerized services, Nginx + Gunicorn (Unix sockets), systemd on VPS/bare-metal and cloud

**Recent wins**

- Monitored and reported events, voter turnout, and vote results from **333 polling stations** for the New Patriotic Party (Ghana) **Presidential Primaries (Jan 31, 2026)**
- Deployed Lotto ERP across **2,000+** point-of-sale (POS) terminals
- Reduced a critical workflow from **3+ minutes → \~50 seconds**
- Supported daily volumes of **100k+** transactions/log events

---

## Current focus

- **Microservices at scale:** service boundaries, contracts, versioning, resiliency patterns, and safe rollouts
- **Big data analysis & reporting infrastructure:** event pipelines, OLTP→OLAP flows, fast dashboards, and operational analytics
- **Payments:** ledgers, idempotency, reconciliation, reversals, dispute workflows, AML/CFT and PCI considerations
- **Django at scale:** DB-first performance (indexes, partitions, materialized views), caching, async where it helps
- **Operations:** predictable deploys, GitOps-style workflows, least-privilege infra, observability (New Relic/Sentry)

---

## Toolkit

**Languages:** Python • SQL • Bash • Go (learning)

**Frameworks:** Django • FastAPI • Sanic • Flask

**Data:** PostgreSQL (+ PostGIS) • TimescaleDB • MSSQL • MySQL • MongoDB • Redis • ClickHouse

**Event streaming & queues:** Kafka • RabbitMQ • NATS (JetStream) • Redis Streams

**Infra/Tools:** $1

**AI dev tools:** Cursor • GitHub Copilot • OpenAI Codex • ChatGPT • Continue.dev

---

## Selected work (projects to pin)

> Most of my production work is private; I can share a short case study on request.

### Election Intelligence & Ops (Canvas)

**Stack:** Kafka • Postgres • ClickHouse • Django • Redis • Nginx • Ubuntu • Python

- Election management system
- Realtime voter turnout dashboard and statistics
- GOTV tools (broadcasts/targeted nudges) and exit‑poll collection
- Voter survey and analytics
- Heatmaps & constituency overlays; observer/incident reports
- Voter canvassing with sentiment analysis
- D-day event monitoring with mapped data and geo-location tracking
- Collation and voter results verification

**Use case (scenario):** New Patriotic Party (Ghana) — Presidential Primary Election 2026

### Lotto ERP

**Stack:** Postgres • TimescaleDB • Django-Ninja-Extra • Django • Redis

- Support point-of-sale (POS) terminal setups
- Flexible jackpot game configuration
- Flexible fixed-odds game configuration
- Flexible game customization (Keno, etc.)
- Retailer wallet management
- Configurable retailer sale rewards structure
- USSD game extension for retailers and players
- Web game extension for arcade games
- Telegram bot for retailers and players’ stakes
- Flexible multi-fintech integration

### Clinexus

**Stack:** Postgres • Django • Django-Ninja-Extra • Redis • Kafka • ClickHouse • Nginx • Ubuntu • Python

- Backbone of healthcare infrastructure
- Patient queue
- Payment integration
- Analytics and outbreak monitors
- Imaging and lab
- Ancillary visits
- Pharmacy
- Inventory management
- FHIR compliant

### Public Procurement Authority Supplier Management Portal

**Stack:** Django • Postgres • Django-Ninja-Extra

- Supplier data management
- Supplier subscription management
- Backoffice portal for approval, document validation, etc.
- Analytic dashboard for management


### Distributed Payment System (Private)

**Stack:** Python • Django • PostgreSQL • Redis • Django-Q2 • Nginx/Gunicorn

- Idempotent payment flows, reversible transactions, audit-grade logging
- KYC/KYB hooks, compliance flags, dispute/reversal workflows
- CI/CD and environment-specific configuration

### Inventory & Storekeeping (Private)

**Django · PostgreSQL**

- Multi-warehouse, batch/lot tracking, stock movement ledger
- Low-stock alerts, suppliers, purchase orders

### USSD Lottery Staking + MoMo (Private)

**Django/FastAPI · PostgreSQL · Redis**

- USSD flows for staking; MoMo integration with tokenized, idempotent debits
- Per-partner branding, rate limiting, audit logging

### Commission & Payouts Engine (Private)

**Django · PostgreSQL**

- Commission rules engine (tiers, windows, exceptions) with reconciliation
- Scheduled payouts, statements, dispute workflows

### Shipmate (Public)

**Python · Docker · GitHub Actions**

- Release/deploy automation for Django/API services (tagging, changelog, build & push)
- Rollback playbook, health checks, environment-specific configs

---

## Open-source & learning

- Using **Django Q2** and contributing small fixes where possible
- Exploring **Go** for high-concurrency services and CLIs

---

## Contact

- **Email:** [andie.89@icloud.com](mailto\:andie.89@icloud.com)
- **LinkedIn:** [https://www.linkedin.com/in/andrew-adu-01276781](https://www.linkedin.com/in/andrew-adu-01276781)
- **Portfolio:** [https://builtbyandie.dev](https://builtbyandie.dev)

Last updated: **Feb 16, 2026**

