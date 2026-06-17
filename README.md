<p align="center">
  <img src="./assets/neon-bar.svg" width="100%" alt="neon divider" />
</p>

<h1 align="center">João Corsi</h1>

<p align="center">
  <b>Engenheiro de Software · Go · Python · TypeScript · Sistemas Distribuídos · Automação com IA</b>
</p>

---

### 👋 Sobre mim

Engenheiro de software com foco em backend e sistemas distribuídos, construindo produtos SaaS reais com Go, Python e TypeScript desde 2022.

Experiência prática em microsserviços em produção, pipelines assíncronos com Kafka e LangGraph, identidade federada com Keycloak e RBAC hierárquico, e automação com LLMs integrada a sistemas de escala real.

Fundador técnico da Corsi Enterprise, liderando time de 10 colaboradores com dois produtos B2B em produção.

---

### 🧠 O que eu faço

- Construo serviços backend com **Go** e **Python**
- Projeto microsserviços e arquiteturas orientadas a eventos com **Kafka**
- Desenvolvo pipelines assíncronos com **Celery** e agentes com **LangGraph**
- Implemento identidade federada, **RBAC** hierárquico e auditoria estruturada
- Integro **LLMs**, automação de voz e transcrição em sistemas de produção
- Monitoro saúde de plataformas com **Prometheus** e **Grafana**

---

### ⚙️ Stack principal

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

### 🚀 Em produção

**Corsi Enterprise** — plataforma de geração de landing pages e CRM personalizado para clientes B2B. Sistema de identidade próprio: autenticação federada com Keycloak, RBAC hierárquico multi-tenant e auditoria estruturada.

**Plataforma de automação multicanal com IA** — +1,85 milhão de mensagens processadas, 101 mil conversas gerenciadas autonomamente por agentes. Média de 8.900 novas conversas/mês, 4 workers assíncronos com 97% de taxa de sucesso em follow-ups, API de integração CRM em Go com retry exponencial.

---

### 🧩 Projetos em destaque

#### C.O.R.S.I — Career · Opportunity · Revenue · System Intelligence · [corsi.dev](https://corsi.dev)

Hub pessoal multi-módulo construído em público. Finance em produção; roadmap: Gym, Diet, Content, Job Radar e hub de agentes IA.

- Arquitetura hexagonal com bounded contexts isolados — violação de fronteira é erro de build
- Contrato de totals REALIZED/PROJECTED/EXCLUDED congelado: exclusão explícita de transfers evita double-counting
- Workspace isolado via `X-Workspace-Id`; autenticação delegada a serviço externo
- 40 testes (17 unitários + 23 integração com Postgres real); migrations forward-only por política
- Prometheus com 11 famílias de métricas customizadas · OTel/Jaeger opt-in · `/health/live` e `/health/ready`

> Stack: Go 1.25 · chi · pgx · React 19 · Vite 8 · Tailwind v4 · TanStack Query v5 · TypeScript 6 · Docker · EasyPanel

---

#### lightweight-saas-backend · [Open Source](https://github.com/JoaoGabrielVianna/lightweight-saas-backend)

Foundation IAM para produtos SaaS em Go, com identidade delegada ao Keycloak 26.

- Autenticação OIDC com JWKS e PKCE — zero password handling no código Go
- Console admin completo: 22 rotas REST + SPA sem dependências externas em `/admin`
- Subsistema de auditoria: 13 ações canônicas com ring buffer em memória
- Rate limiting por IP antes da autenticação (token bucket, 10 req/s, burst 20)
- 23 probes de segurança black-box validados · CodeQL automatizado · gaps documentados publicamente
- Bootstrap em um comando · documentação bilíngue (PT-BR/EN) · runbooks de produção

> Stack: Go 1.25 · Gin · PostgreSQL 15 · Keycloak 26 · Docker Compose · GitHub Actions

---

### 📬 Contato

<p align="center">
  <a href="mailto:joaogabrielvianna05@gmail.com">Email</a> •
  <a href="https://www.linkedin.com/in/joaogabrielvianna/">LinkedIn</a> •
  <a href="https://joaogabrielvianna.com.br">Portfolio</a>
</p>

<p align="center">
  <strong>Construindo sistemas confiáveis com clareza, responsabilidade e escala.</strong>
</p>