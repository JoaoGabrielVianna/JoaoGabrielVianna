   <p align="center">
  <img src="./assets/neon-bar.svg" width="100%" alt="neon divider" />
</p> 
   
<h1 align="center">João Corsi</h1>   
     
<p align="center">
  <b>Software Engineer · Go · Python · TypeScript · Distributed Systems · AI Automation</b>
</p> 

---

### 👋 About me

Backend-focused software engineer building real SaaS products with Go, Python, and TypeScript since 2022.

Hands-on experience with production microservices, async pipelines with Kafka and LangGraph, federated identity with Keycloak and hierarchical RBAC, and LLM automation integrated into real-scale systems.

Currently building distributed backend systems and AI-integrated platforms.

---

### 🧠 What I do

- Build backend services with **Go** and **Python**
- Design event-driven architectures and microservices with **Kafka**
- Develop async pipelines with **Celery** and AI agents with **LangGraph**
- Implement federated identity, hierarchical **RBAC**, and structured audit systems
- Integrate **LLMs**, voice automation, and real-time transcription into production
- Monitor platform health with **Prometheus** and **Grafana**

---

### ⚙️ Core stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" height="45" title="Go" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="45" title="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="45" title="TypeScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="45" title="React" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="45" title="PostgreSQL" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="45" title="Docker" />
</p>

<p align="center">
  Go · FastAPI · LangGraph · Keycloak · Kafka · Celery · PostgreSQL · Docker · GitHub Actions · Prometheus · Grafana
</p>

---

### 🚀 In production

- AI-powered multichannel automation platform: **+1.85M messages processed**, 101K conversations managed autonomously by agents
- Average of **8,900 new conversations/month**, 4 async workers with **97% success rate** on automated follow-ups
- CRM integration API in Go with exponential backoff retry: **89.3% webhook success rate** against an external system

---

### 🧩 Featured projects

#### C.O.R.S.I — Career · Opportunity · Revenue · System Intelligence

Personal multi-module hub built in public. Finance module in production; roadmap: Gym, Diet, Content, Job Radar, and AI agents hub.

- Hexagonal architecture with isolated bounded contexts — boundary violation is a build error
- Frozen REALIZED/PROJECTED/EXCLUDED totals contract: explicit transfer exclusion prevents double-counting
- Workspace isolation via `X-Workspace-Id`; authentication delegated to an external service
- 40 tests (17 unit + 23 integration against real Postgres); forward-only migrations by policy
- Prometheus with 11 custom metric families · OTel/Jaeger opt-in · `/health/live` and `/health/ready`

> Stack: Go 1.25 · chi · pgx · React 19 · Vite 8 · Tailwind v4 · TanStack Query v5 · TypeScript 6 · Docker · EasyPanel

---

#### lightweight-saas-backend · [Open Source](https://github.com/JoaoGabrielVianna/lightweight-saas-backend)

IAM foundation for SaaS products in Go, with identity delegated to Keycloak 26.

- OIDC authentication with JWKS and PKCE — zero password handling in Go code
- Full admin console: 22 REST routes + dependency-free SPA at `/admin`
- Audit subsystem: 13 canonical actions with in-memory ring buffer
- IP-level rate limiting before authentication (token bucket, 10 req/s, burst 20)
- 23 black-box security probes validated · automated CodeQL · gaps tracked publicly
- One-command bootstrap · bilingual docs (PT-BR/EN) · production runbooks

> Stack: Go 1.25 · Gin · PostgreSQL 15 · Keycloak 26 · Docker Compose · GitHub Actions

---

### 📬 Contact

<p align="center">
  <a href="mailto:joaogabrielvianna05@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/joaogabrielvianna/">LinkedIn</a> •
  <a href="https://joaogabrielvianna.com.br">Portfolio</a>
</p>

<p align="center">
  <strong>Building reliable systems with clarity, ownership, and scale.</strong>
</p>
