<h1 align="left">Andrii Manzhola</h1>

<p align="left">
  <b>Co-Founder @ <a href="https://seog.ai">SEOG</a> · software architect · AI-agent engineer</b><br/>
  I design and ship AI SaaS products end to end — architecture, backend, frontend, infra, launch.
</p>

<p align="left">
  <a href="mailto:andreimanzhola@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://linkedin.com/in/andrii-manzhola-372a8133b"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://calendly.com/andrei47892/30min"><img src="https://img.shields.io/badge/Book_a_call-006BFF?style=for-the-badge&logo=calendly&logoColor=white" alt="Calendly"/></a>
</p>

---

## 🚀 What I'm building

Eight products taken from idea to production — I own the architecture on all of them and write most of the code.

| Product | What it does | |
| --- | --- | --- |
| **SEOG** | AI local-SEO platform — Google Business Profile management, map-pack geo-grid rank tracking, review sync + published replies, competitor and AI-visibility intelligence. NestJS + Next.js, with an MCP server so agents can run local SEO from the terminal. | [seog.ai](https://seog.ai) |
| **VidVibe** | AI video platform — generation, editing and multi-channel publishing. Next.js app, NestJS + BullMQ pipeline, FastAPI ML service (speech-to-text, smart reframe). | [vidvibe.io](https://vidvibe.io) |
| **Terminal Skills** | Marketplace and open library of AI-agent skills — portable `SKILL.md` files for Claude Code, Codex, Gemini CLI and Cursor, plus an npm CLI and an LLM-backed validator. | [terminalskills.io](https://terminalskills.io) |
| **c10r** | Multi-tenant CRM with an AI gateway on top — task routing across hosted and self-hosted models, receipt parsing, voice UI, workspace-level identity. | [c10r.io](https://c10r.io) |
| **Skyline** | Deployment platform that takes a local-business site from repo to live on Cloudflare — stateless control panel driving the Cloudflare and GitHub APIs. | — |
| **Card Forge** | Multi-tenant SaaS for digital smart cards — sellers create, theme and manage cards; image generation built into the editor. | — |
| **Live Bridge** | Live speech translation running entirely on local AI — Whisper + NLLB on GPU, sub-second turnaround, no cloud dependency. | — |
| **3D Drone Tour** | Browser-native 3D tour engine — drone capture turned into a navigable property walkthrough with floor-plan sync. | — |

---

## 🛠 How I work

**Architecture.** Multi-tenant SaaS, event-driven backends, monorepos with shared contracts, Postgres/Mongo data modelling, and the boring discipline that keeps them maintainable — typed boundaries, migrations, real CI.

**AI-agent engineering.** This is where most of my time goes now: agent orchestration and fleets, MCP servers and tool design, RAG with vector search, self-hosted inference next to hosted models with failover routing, and OpenTelemetry-based observability so agent behaviour is measurable instead of vibes.

**Infrastructure.** Docker, Cloudflare Workers, Coolify, GPU boxes for local inference, LGTM stack for metrics/logs/traces. I deploy what I build and I'm on call for it.

**Product.** Payments, auth, i18n and RTL, SEO, transactional email, and the unglamorous integration work that decides whether a product actually ships.

---

## 📖 Open source

- **[TerminalSkills/skills](https://github.com/TerminalSkills/skills)** — open library of AI-agent skills. `SKILL.md` files that drop into Claude Code, Codex, Gemini CLI or Cursor and teach an agent a task.
- **[seog-ai/local-seo-manual](https://github.com/seog-ai/local-seo-manual)** — a free, hands-on manual for local SEO: how Google ranks businesses in the map pack, 49 chapters, real labs and a probe-verified field reference.

---

## ⚙️ Stack

**Languages**\
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Backend**\
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Frontend**\
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)

**AI / agents**\
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square)

**Data**\
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Infra & observability**\
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<p align="left">
  Open to partnerships, product collaborations and interesting architecture problems.<br/>
  <a href="https://calendly.com/andrei47892/30min"><b>Book 30 minutes →</b></a>
</p>
