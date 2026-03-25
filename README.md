# James C. Young — AreteDriver

**AI Systems Engineer | 11 PyPI Packages | 7 Live Deployments | 36,000+ Tests**
Python · Rust · TypeScript · FastAPI · Sui Move · Full CI/CD

I spent 17 years building reliable systems in manufacturing (IBM, Toyota) — then applied that discipline to AI engineering. The result: production systems with real users, real billing, and real test coverage. Not demos. Not prototypes. Shipped software.

**[Portfolio](https://aretedriver.dev)** · **[LinkedIn](https://linkedin.com/in/jamesy-3b77b3120)** · **[Substack](https://substack.com/@aretedriver)** · Portland, OR

---

## Featured Projects

### [Animus](https://github.com/AreteDriver/animus) — Multi-Agent Orchestration Framework
Coordinate specialized AI agents with budget controls, quality gates, and checkpoint/resume. Self-improvement loop with Ollama. MCP server for Claude Code integration.
FastAPI · React · 4 packages (Core/Forge/Quorum/Bootstrap) · 37 tools · **14,748 tests · 97% coverage** · [Quorum on PyPI](https://pypi.org/project/convergentAI/)

### [BenchGoblins](https://benchgoblins.com) — AI Fantasy Sports Decision Engine *(Live)*
Scored LLM routing (Grok-primary, Claude fallback), 14 commissioner tools, Goblin Verdict scoring. Stripe billing. Dual-token auth.
Next.js · FastAPI · PostgreSQL · Redis · **2,873 tests · 98% coverage** · [benchgoblins.com](https://benchgoblins.com)

### [EVE Gatekeeper](https://edengk.com) — Route Intelligence Platform *(Live)*
14-layer interactive map, gate camp warnings, expandable risk breakdowns per hop, SSO auth, Stripe billing. Public repo.
Next.js · FastAPI · SQLite · **3,296 tests** · [edengk.com](https://edengk.com) · [GitHub](https://github.com/Arete-Consortium/Gatekeeper)

### [DOSSIER](https://github.com/AreteDriver/Dossier) — Document Intelligence Platform
Investigative-grade analysis: ingest PDFs/emails/scans, extract 4 NER entity types, surface co-occurrence relationships. Zero cloud dependencies.
SQLite FTS5 · Custom NER · Auto-classification · **1,084 tests · 97% coverage**

### [Argus Overview](https://github.com/AreteDriver/Argus_Overview) — Linux Multi-Window Manager for EVE Online
Real-time 30 FPS window previews, team management, auto-tiling. Wayland support. Cross-platform.
**26,000+ downloads** · 36 releases · **2,184 tests · 100% coverage** · [PyPI](https://pypi.org/project/argus-overview/)

---

## EVE Frontier Hackathon — On-Chain Intelligence (Sui)

### [WatchTower / Witness](https://github.com/AreteDriver/witness) — On-Chain Intelligence & Dossier NFTs *(Live)*
16 Discord commands, Dossier NFT minting (3 tiers), Oracle Loop for entity profiling, reputation cache, Stripe + SUI payments.
FastAPI · Sui Move · Discord.py · dApp Kit · **817 tests**

### [Monolith](https://github.com/AreteDriver/monolith) — Anomaly Detection Engine *(Live)*
35 detection rules, 17 checkers, chain state via Sui GraphQL, public API v1, webhook subscriptions, Canvas2D heatmap with 24K systems.
FastAPI · SQLite · Sui GraphQL · **296 tests · 80% coverage gate**

### [Frontier Tribe OS](https://github.com/AreteDriver/frontier-tribe-os) — Corp Operations Dashboard *(Live)*
Kill Feed, LLM Briefing, System Intelligence, Alert Config, Pilot/Corp Intel, Battle Reports, Signature Resolution.
Next.js · FastAPI · 7 modules · Role-gated access

---

## Published Developer Tools — [PyPI](https://pypi.org/user/AreteDriver/)

| Tool | What | Tests | Install |
|------|------|------:|---------|
| [anchormd](https://github.com/Arete-Consortium/anchormd) | AI agent context file generator/auditor + tech debt scanner · [anchormd.dev](https://anchormd.dev) | 693 | `pip install anchormd` |
| [agent-lint](https://github.com/AreteDriver/agent-lint) | Workflow YAML cost estimator + anti-pattern linter | 565 | `pip install agentlinter` |
| [context-hygiene](https://github.com/AreteDriver/context-hygiene) | Context window bloat detection + signal density scoring | 398 | `pip install context-hygiene` |
| [promptctl](https://github.com/AreteDriver/promptctl) | Claude API toolkit — prompt engineering, code review, doc intelligence | 330 | `pip install promptctlai` |
| [memboot](https://github.com/AreteDriver/memboot) | Zero-infra persistent memory for LLMs — SQLite + TF-IDF | 292 | `pip install memboot` |
| [ai-spend](https://github.com/AreteDriver/ai-spend) | AI API cost aggregator — Anthropic + OpenAI in one view | 267 | `pip install ai-spend` |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | MCP server manager across agentic IDEs | 159 | `pip install arete-mcp` |
| [convergentAI](https://github.com/AreteDriver/convergent) | Multi-agent conflict resolution — Python + Rust (PyO3) | 900 | `pip install convergentAI` |
| [G13-Linux](https://github.com/AreteDriver/G13_Linux) | Logitech G13 Linux driver — PyQt6 GUI, WebSocket API | 1,641 | `pip install G13-Linux` |
| [argus-overview](https://github.com/AreteDriver/Argus_Overview) | EVE Online multi-window manager | 2,184 | `pip install argus-overview` |
| [LikX](https://github.com/AreteDriver/LikX) | Screenshot + annotation + OCR for Linux | 1,752 | `pip install LikX` |

---

## Infrastructure

**80+ CI/CD workflows · 0 code scanning alerts · 0 dependabot alerts**

| | |
|---|---|
| **Deployments** | 9 services on Fly.io + Vercel — BenchGoblins, Gatekeeper, WatchTower, Monolith, Tribe OS, anchormd, AI Cards, StayCards, license server |
| **Containers** | Multi-stage Dockerfiles, docker-compose, multi-arch builds (amd64 + arm64) |
| **Orchestration** | Kubernetes (Deployments, HPA, Ingress), Helm charts, Kustomize |
| **Security** | CodeQL + gitleaks + Bandit + Semgrep + Trivy + pip-audit across all repos |
| **Publishing** | 11 PyPI packages via OIDC trusted publishing (zero stored tokens) |
| **Billing** | Stripe integration (payments, webhooks, license key generation) on 3 products |

---

## By the Numbers

| | |
|---|---|
| **Tests** | 36,000+ verified across active repos |
| **PyPI packages** | 11 published, 2 with 16+ releases |
| **Live systems** | 9 production deployments with real users |
| **Argus downloads** | 26,000+ (36 releases on PyPI) |
| **CI workflows** | 80+ across 20 repositories |
| **Security alerts** | 0 code scanning, 0 dependabot — fleet-wide |

---

## Technical Stack

| Domain | Tools |
|---|---|
| Languages | Python, Rust, TypeScript |
| AI/ML | Claude API, OpenAI, Grok, Ollama, multi-agent orchestration |
| Backend | FastAPI, SQLAlchemy, PostgreSQL, SQLite, Redis |
| Frontend | React, Next.js, React Native/Expo, PySide6 |
| Blockchain | Sui Move, GraphQL, dApp Kit |
| Infrastructure | Docker, Kubernetes, Helm, GitHub Actions, Fly.io, Vercel |
| Security | CodeQL, Bandit, Semgrep, Trivy, gitleaks, SAST pipelines |

---

## Engineering Philosophy

I scaled an ice cream line from 740 pints/day to 4,800/hour using Kaizen. I apply the same thinking to software: standard work, visual management, poka-yoke, jidoka. Operational reliability over algorithmic elegance. A system that ships predictably beats one that demos brilliantly.
