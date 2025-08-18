<!--
Replace the placeholders before publishing:
- YOUR_EMAIL → contact email (optional)
- YOUR_LINKEDIN → full LinkedIn URL (optional)
-->

# andie adu — Backend Engineer · DevOps/SRE · Database Specialist

Fintech & distributed systems · High‑throughput APIs · Secure, observable services

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrew-adu-01276781/)
[![Email](https://img.shields.io/badge/Email-Contact-informational?logo=gmail&logoColor=white)](mailto:andie.89@icloud.com)
[![Website](https://img.shields.io/badge/Website-Portfolio-success?logo=google-chrome&logoColor=white)](https://builtbyandie.dev)

---

## About me

- Backend engineer with strong DevOps/SRE habits and a database background (PostgreSQL, MSSQL, MySQL, Redis).
- Build and operate payment & revenue collection systems, inventory and map‑aware apps (PostGIS), and high‑reliability
  APIs.
- Comfortable on bare‑metal/VPS as well as cloud (AWS · Azure · GCP). CI/CD with GitHub Actions.
- Pragmatic, security‑minded (MFA, RBAC, audit trails) with deep care for logs, metrics and tracing (Sentry, New Relic).
- Recent wins: reduced a critical workflow from **3+ minutes → ~50 seconds**; supported daily volumes of **100k+**
  transactions/log events.

## What I’m focusing on

- **Payments**: resilient ledgers, idempotency, reconciliation, AML/CFT and PCI considerations.
- **Django @ scale**: async views where useful, DB‑first performance (indexes, partitions, materialized views), caching.
- **Ops**: predictable deploys, GitOps‑y workflows, least‑privilege infra, incident response playbooks.

## Tech I use day‑to‑day

**Languages:** Python, SQL, Bash, Go (learning)

**Frameworks:** Django, FastAPI, Lumen (PHP), Sanic, Flask

**Data:** PostgreSQL (+ PostGIS), MSSQL, MySQL, MongoDB, Redis

**Infra/Tools:** Linux, Nginx, Gunicorn (Unix sockets), Systemd, Docker, GitHub Actions, Poetry, New Relic, Sentry

---

## Highlights (projects to pin)

### 1) Distributed Payments Platform (📌)

**Stack:** Python · Django · PostgreSQL · Redis · Django‑Q2 · Nginx/Gunicorn

- Idempotent payment flows · reversible transactions · audit‑grade logging
- KYC/KYB hooks · compliance flags · dispute/reversal workflows
- CI/CD with GitHub Actions; environment‑specific settings

**Repo:** Private (case study on request)

---

### 2) Inventory & Storekeeping (📌)

**Stack:** Django · PostgreSQL · Celery/Queues · DRF

- Multi‑warehouse, batch/lot, movement ledger
- Low‑stock alerts; supplier and purchase orders

**Repo:** Private (case study on request)

---

### 3) USSD Lottery Staking with MoMo (📌)

**Stack:** Django/FastAPI · PostgreSQL · Redis

- USSD short‑code flows for staking
- Mobile money (MoMo) integration; tokenised payments; idempotent debits
- Per‑partner branding for media organizations; rate limits; audit logs

**Repo:** Private (case study on request)

---

### 4) Election Monitoring Platform (📌)

**Stack:** Django · Channels/WebSockets · PostgreSQL · Redis · PostGIS (optional)

- Realtime voter turnout dashboard and statistics
- GOTV tools (broadcasts/targeted nudges) and exit‑poll collection
- Heatmaps & constituency overlays; observer/incident reports

**Repo:** Private (case study on request)

---

### 5) Commission & Payouts for Lottery Marketing Companies (📌)

**Stack:** Django · PostgreSQL · Celery/Queues

- Commission rules engine (tiers, time windows, exceptions) with reconciliation
- Scheduled payouts, transactional statements, and dispute workflows

**Repo:** Private (case study on request)

---

### 6) Map/Geo Sample with PostGIS (📌)

**Stack:** Django · PostGIS

- `geography=True` usage examples, spatial indexes, distance queries, tile caching notes

**Repo:** Private (case study on request)

---

### 7) Telegram WebApp + Django starter (📌)

**Stack:** Django · DRF · Telegram Web Apps

- Inline keyboards + web‑app flows, session store patterns, enum/stack‑based navigation

**Repo:** Private (case study on request)

---

### 8) Shipmate (📌)

**Stack:** Python · GitHub Actions · Docker

- Release & deploy automation for Django/API services (tagging, changelog, image build & push)
- Rollback playbook, health checks, and environment‑specific configs

**Repo:** https://github.com/andrewadu/shipmate

---

## Open‑source & learning

- Using **Django Q2**, reporting issues and small patches where possible.
- Exploring **Go** for high‑concurrency services and CLIs.

## Writing

- Google Cloud Fundamentals – Core Infrastructure (notes & quiz prompts).
- Incident checklists and postmortem template.

## Contact

- Email: andie.89@icloud.com · LinkedIn: https://www.linkedin.com/in/andrew-adu-01276781 ·
  Portfolio: https://builtbyandie.dev

<sub>Last updated: **Aug 14, 2025**</sub>

---
