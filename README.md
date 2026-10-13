# JeanFranck (Evan) Oboumou
### Lead Software Architect · Systems Engineer · Founder of BeOjefe & MEOCE

<p align="left">
  <img src="https://img.shields.io/badge/Architecture-Distributed%20Systems-0ea5e9?style=flat-square" />
  <img src="https://img.shields.io/badge/FinTech-BRVM%20Market%20Data-10b981?style=flat-square" />
  <img src="https://img.shields.io/badge/Security-Zero--Trust%20%7C%20OpenBao-f59e0b?style=flat-square" />
  <img src="https://img.shields.io/badge/Infrastructure-Proxmox%20LXC%20%26%20Tailscale-6366f1?style=flat-square" />
</p>

---

## 🏛️ About Me

Lead Software Architect and Systems Engineer based between Casablanca and Libreville, building mission-critical digital infrastructure engineered from the ground up for African markets.

I specialize in **low-latency financial data streaming**, **high-concurrency distributed backends**, and **zero-trust infrastructure automation**. I design systems under uncompromising constraints: bandwidth volatility, resilient offline capabilities, mobile-first flows, and 100% zero-downtime reliability.

---

## 🚀 Flagship Initiatives

### 📈 [MEOCE](https://meocehub.com) — Financial Intelligence Suite for BRVM
*The first institutional-grade market data, charting, and analytics ecosystem for the Bourse Régionale des Valeurs Mobilières (WAEMU).*
- **Real-Time Data Engine**: High-frequency intraday scraping and normalization pipeline delivering sub-second order book and trade book updates.
- **Architectural Backbone**: FastAPI microservices, Next.js 16 reactive charting engine, Redis Streams, PostgreSQL 18 with pgvector, and automated Airflow data pipelines.
- **WhatsApp Integration**: Conversational market alerts and portfolio updates powered by self-hosted WAHA gateways.

### ⚡ [BeOjefe Studio](https://beojefe.com) — African Digital Engineering Studio
*Engineering products that work in the real world, for real African users.*
- **Philosophy**: Built for Africa from line one — not retrofitted. High latency, mobile money integrations, and real-world network constraints are starting assumptions, not afterthoughts.

---

## 🛠️ Technical Stack & Core Disciplines

| Layer | Technologies & Paradigms |
|---|---|
| **Languages & Runtimes** | Python 3.11+, TypeScript, Node.js 20+, Rust, Modern Bash |
| **Backend & Microservices** | FastAPI, Celery, uv, Pydantic v2, Redis, Apache Airflow |
| **Frontend & UI** | Next.js 16 (App Router), React 19, Tailwind CSS v4, Lightweight Charts |
| **Data & Storage** | PostgreSQL 18 (pgvector), Garage S3 Object Storage, Redis, Restic |
| **Security & Secrets** | OpenBao (Vault v2) KV Engine, GitHub OIDC Auth (Zero permanent tokens), MTLS |
| **Infrastructure & Mesh** | Proxmox VE LXC Clustering, Docker Compose, Tailscale Mesh, HAProxy, Cloudflare |
| **CI/CD & Governance** | GitHub Actions (Strict Issue -> Branch -> PR -> CD), Dokploy, Vercel |

---

## 📐 Engineering Principles

1. **Zero Permanent Secrets in CI**: Every automated pipeline authenticates dynamically via OIDC with ephemeral 15-minute tokens.
2. **Deterministic Governance**: No direct pushes to main, strict semantic versioning, reproducible environments via lockfiles and containerized builds.
3. **Resilient Local-First**: Offline fallback modes, graceful degradation, and resilient state synchronization.
4. **Zero-Waste Hygiene**: Pristine repository roots, isolated test fixtures, and automated resource reclamation.

---

## 📬 Connect

- **Website**: [beojefe.com](https://beojefe.com)
- **MEOCE Platform**: [meocehub.com](https://meocehub.com)
- **Email**: [jfe.oboumou@gmail.com](jfe.oboumou@gmail.com)
- **LinkedIn**: [linkedin.com/in/jeanfranck-oboumou](https://www.linkedin.com/in/jean-franck-evan-oboumou-b09593423/)
