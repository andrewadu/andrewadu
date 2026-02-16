# Andrew Adu (Andie Adu) — Backend Engineer · DevOps/SRE · Data Systems

Fintech & distributed systems • High-throughput APIs • Secure, observable services

---

## What I do

I build and run backend systems where correctness, uptime, and auditability matter.

- **Backend + databases:** PostgreSQL (incl. PostGIS), MSSQL, MySQL, Redis, MongoDB
- **Reliability mindset:** logs/metrics/traces, incident playbooks, least-privilege access, audit trails
- **Delivery:** CI/CD with GitHub Actions, Dockerized services, Nginx + Gunicorn (Unix sockets), systemd on VPS/bare-metal and cloud

**Recent wins**

- Monitored and reported events, voter turnout, and vote results from **333 polling stations** for the New Patriotic Party (Ghana) **Presidential Primaries (Jan 31, 2026)**.
- Deployed Lotto ERP across **2,000+** point-of-sale (POS) terminals.
- Reduced a critical workflow from **3+ minutes → \~50 seconds**.
- Supported daily volumes of **100k+** transactions/log events.

---

## Current focus

- **Microservices at scale:** service boundaries, contracts, versioning, resiliency patterns, and safe rollouts.
- **Big data analysis & reporting infrastructure:** event pipelines, OLTP→OLAP flows, fast dashboards, and operational analytics.
- **Payments:** ledgers, idempotency, reconciliation, reversals, dispute workflows, AML/CFT and PCI considerations.
- **Django at scale:** DB-first performance (indexes, partitions, materialized views), caching, async where it helps.
- **Operations:** predictable deploys, GitOps-style workflows, least-privilege infra, observability (New Relic/Sentry).

---

## Toolkit

**Languages:** Python • SQL • Bash • Go (learning)

**Frameworks:** Django • FastAPI • Sanic • Flask • Django-Ninja-Extra

**Data:** PostgreSQL (+ PostGIS) • TimescaleDB • MSSQL • MySQL • MongoDB • Redis • ClickHouse

**Event streaming & queues:** Kafka • RabbitMQ • NATS (JetStream) • Redis Streams

**Infra/Tools:** Linux (Ubuntu) • Nginx • Gunicorn • Uvicorn • systemd • Docker • GitHub Actions • Poetry • New Relic • Sentry

**AI dev tools:** Cursor • GitHub Copilot • OpenAI Codex • ChatGPT • Continue.dev

---

## Selected work (projects to pin)

> Most of my production work is private; I can share a short case study on request.

### Election Intelligence & Ops (Canvas)

**Stack:** Kafka • Postgres • ClickHouse • Django • Redis • Nginx • Ubuntu • Python

- Runs an election management system for polling-station onboarding, roles, workflows, and audit trails.
- Provides a real-time turnout dashboard with polling-station rollups and anomaly flags.
- Supports GOTV broadcasts and targeted nudges, plus structured exit-poll collection in the field.
- Captures voter surveys and produces analytics for segmentation, trends, and performance tracking.
- Generates heatmaps and constituency overlays, with observer and incident reporting (notes, photos, and timestamps).
- Enables canvassing workflows with sentiment analysis on responses and field notes.
- Monitors D-Day operations on a live map with geolocation tracking and time-based event logs.
- Handles collation workflows and vote-result verification with reconciliation against station submissions.

**Use case (scenario):** New Patriotic Party (Ghana) — Presidential Primary Election 2026

### Lotto ERP

**Stack:** Postgres • TimescaleDB • Django-Ninja-Extra • Django • Redis

- Supports POS terminal onboarding, device provisioning, and outlet-level configuration.
- Configures jackpot games with flexible rules, schedules, and payout parameters.
- Runs fixed-odds games with configurable markets, odds tables, and settlement rules.
- Enables custom game templates (Keno and more) with per-product branding and rule sets.
- Manages retailer wallets (float, commissions, settlements) with full ledgering and statements.
- Implements configurable retailer sales rewards (tiers, thresholds, campaigns) with transparent reporting.
- Extends gameplay via USSD for retailers and players with session-safe, resilient flows.
- Adds a web channel for arcade-style games with secure stake, payout, and account handling.
- Provides a Telegram bot for retailer and player stakes, notifications, and balance checks.
- Integrates multiple fintech providers through a pluggable adapter layer with routing and failover.

### Clinexus

**Stack:** Postgres • Django • Django-Ninja-Extra • Redis • Kafka • ClickHouse • Nginx • Ubuntu • Python

- Serves as the backbone of a healthcare infrastructure platform, connecting clinical and operational workflows.
- Manages patient queueing end-to-end (triage, routing, and visit states) across facilities.
- Integrates payments for visits, services, and pharmacy with reconciliation and receipts.
- Delivers analytics and outbreak surveillance dashboards for management and public health.
- Supports imaging and lab workflows, including orders, results, and attachments.
- Tracks ancillary visits as structured encounters (vitals, nursing notes, procedures, follow-ups).
- Runs pharmacy operations for dispensing, pricing, and stock-linked fulfillment.
- Provides inventory management across stores and departments with stock movement history.
- Is FHIR-compliant for interoperability and includes CDC code integration.

### Public Procurement Authority Supplier Management Portal

**Stack:** Django • Postgres • Django-Ninja-Extra

**Link:** [https://suppliers.ppa.gov.gh](https://suppliers.ppa.gov.gh)

- Centralizes supplier data management with structured profiles and document records.
- Manages supplier subscriptions, renewals, and status tracking.
- Provides a backoffice portal for approvals, validations, and operational workflows.
- Offers an analytics dashboard for management reporting and oversight.

### Distributed Payment System (Private)

**Stack:** Python • Django • PostgreSQL • Redis • Django-Q2 • Nginx/Gunicorn

- Implements idempotent payment flows, reversible transactions, and audit-grade logging.
- Supports KYC/KYB hooks, compliance flags, and dispute and reversal workflows.
- Ships with CI/CD automation and environment-specific configuration.

### Inventory & Storekeeping (Private)

**Stack:** Django • PostgreSQL

- Tracks stock movement as a ledger across warehouses, branches, and transfers.
- Supports batching and expiry workflows with history and audit trails.

### USSD Lottery Staking + MoMo (Private)

**Stack:** Django/FastAPI • PostgreSQL • Redis

- Runs USSD staking flows with resilient sessions, retries, and idempotent debits.
- Integrates MoMo providers with rate limiting, auditing, and per-partner branding.

### Commission & Payouts Engine (Private)

**Stack:** Django • PostgreSQL

- Applies configurable commission rules (tiers, windows, exceptions) with reconciliation.
- Produces statements and schedules payouts with approval workflows.

### Shipmate (Public)

**Stack:** Python • Docker • GitHub Actions

- Automates release and deploy workflows (tagging, changelogs, build and push).
- Includes rollback playbooks, health checks, and environment-specific configuration.

---

## Open-source & learning

- Using **Django Q2** and contributing small fixes where possible.
- Exploring **Go** for high-concurrency services and CLIs.

---

## Contact

- **Email:** [andie.89@icloud.com](mailto\:andie.89@icloud.com)
- **LinkedIn:** [https://www.linkedin.com/in/andrew-adu/](https://www.linkedin.com/in/andrew-adu/)
- **Portfolio:** [https://builtbyandie.dev](https://builtbyandie.dev)

Last updated: **Feb 16, 2026**

