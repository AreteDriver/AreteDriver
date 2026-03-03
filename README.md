# James C. Young

**AI Infrastructure Builder** — I build the systems that make AI agents work in production: orchestration runtimes, coordination protocols, budget controls, and resilience patterns.

17 years in manufacturing operations. Self-taught engineer. Now building production infrastructure for AI systems.

---

## Flagship

### [Animus](https://github.com/AreteDriver/animus)
AI exocortex and multi-agent orchestration monorepo. Four packages: Core (personal AI with memory and learning), Forge (workflow runtime with budget enforcement, quality gates, and checkpoints), Quorum (decentralized coordination protocol, [live on PyPI](https://pypi.org/project/convergentAI/)), and Bootstrap (install daemon and dashboard).

**13,100+ tests · 96-97% coverage per package** · Python · PyO3 · MIT

### [BenchGoblins](https://github.com/Arete-Consortium/BenchGoblins)
League-centric AI fantasy sports decision engine. Next.js frontend + React Native mobile + FastAPI backend + PostgreSQL + Redis. Deployed to production on Fly.io + Vercel.

**1,988 tests · 99% coverage** · Python · TypeScript · [benchgoblins.com](https://benchgoblins.com)

### [RedOPS](https://github.com/AreteDriver/RedOPS)
Offensive security operations platform. Recon, scanning, vulnerability analysis, and reporting — orchestrated through structured pipelines with full audit trails.

**5,074 tests** · Python · Docker · Multi-arch (amd64 + arm64) · MIT

### [Dossier](https://github.com/AreteDriver/Dossier)
Local-first document intelligence. NER, classification, OCR, full-text search, forensics timeline, and entity graph analysis — all on SQLite with zero cloud dependencies.

**1,055 tests · 97% coverage** · Python · FastAPI · MIT

---

## CI/CD & Infrastructure

**83 workflow files across 20 repos. 0 open code scanning alerts.**

| Capability | Evidence |
|---|---|
| **Containerization** | Multi-stage Dockerfiles, docker-compose (5 services), [templates](https://github.com/AreteDriver/ci-templates) |
| **Kubernetes** | Deployments, HPA (2-10 pods), Ingress, Kustomize, Helm chart — [K8s manifests](https://github.com/AreteDriver/ci-templates/tree/main/kubernetes) |
| **CI Pipelines** | Lint → test → SAST → build → deploy across Python, Rust, TypeScript |
| **Security Scanning** | CodeQL + gitleaks + Bandit + Semgrep + Trivy + TruffleHog + pip-audit |
| **Live Deployments** | [BenchGoblins](https://benchgoblins.com) on Fly.io + Vercel, 4 packages on PyPI via OIDC |
| **Monitoring** | Prometheus alerting (14 rules), OpenTelemetry tracing — [alert rules](https://github.com/AreteDriver/ci-templates/tree/main/monitoring) |
| **Benchmarks** | Automated performance regression tracking on gh-pages (3 repos) |

---

## Dev Tools

| Tool | What | Tests |
|------|------|------:|
| [promptctl](https://github.com/AreteDriver/promptctl) | Claude API toolkit — prompt engineering, code review, doc intelligence | 286 |
| [memboot](https://github.com/AreteDriver/memboot) | Zero-infra persistent memory for LLMs — SQLite + TF-IDF vector search ([PyPI](https://pypi.org/project/memboot/)) | 285 |
| [claudemd-forge](https://github.com/Arete-Consortium/claudemd-forge) | CLAUDE.md generator/auditor for AI coding agents ([PyPI](https://pypi.org/project/claudemd-forge/)) | 569 |
| [ai-spend](https://github.com/AreteDriver/ai-spend) | AI API cost aggregator — Anthropic + OpenAI billing in one view | 222 |
| [agent-audit](https://github.com/AreteDriver/agent-audit) | Workflow YAML cost estimator + linter for agent pipelines | 193 |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | MCP server manager — discover, monitor, manage across IDEs | 139 |

---

## Also Built

| Project | What | Tests |
|---------|------|------:|
| [Argus Overview](https://github.com/AreteDriver/Argus_Overview) | EVE Online multi-boxing tool for Linux + Windows (2,500+ downloads) | 1,892 |
| [Convergent](https://github.com/AreteDriver/convergent) | Multi-agent coordination library — intent graphs, consensus, stigmergy ([PyPI](https://pypi.org/project/convergentAI/)) | 904 |
| [marketing-engine](https://github.com/AreteDriver/marketing-engine) | LLM-powered content pipeline + platform API publishing | 581 |
| [TideWise](https://github.com/AreteDriver/tidewise) | Fishing forecast engine — solunar, tides, pressure, 7 scoring factors | 373 |
| [ai-skills](https://github.com/AreteDriver/ai-skills) | 70 production skills for Claude Code agents | — |

---

## Products — [Arete Consortium](https://github.com/Arete-Consortium)

| Product | What |
|---------|------|
| [BenchGoblins](https://github.com/Arete-Consortium/BenchGoblins) | AI fantasy sports engine — live on Fly.io + Vercel · [benchgoblins.com](https://benchgoblins.com) |
| [Herald](https://github.com/Arete-Consortium/Herald) | Automated social promotion for GitHub releases — Reddit, X, LinkedIn |

---

## Proof

| | |
|---|---|
| **Tests across active repos** | 30,700+ |
| **Projects with CI green** | 20 |
| **Live deployments** | BenchGoblins (Fly.io + Vercel), 4 packages on PyPI |
| **Security posture** | 0 code scanning alerts across all repos |

---

## Technical Profile

**Languages:** Python, Rust, TypeScript
**Frontend:** React, Next.js, React Native/Expo, PySide6, HTMX
**Backend:** FastAPI, SQLAlchemy, Alembic, WebSocket, Redis pub/sub
**Database:** PostgreSQL, SQLite (WAL + FTS5), ChromaDB, Redis
**Infrastructure:** Docker, Kubernetes, Helm, GitHub Actions, Fly.io, Vercel, Prometheus
**AI:** Claude API, OpenAI, Ollama, multi-agent orchestration, MCP servers
**Security:** CodeQL, Bandit, Semgrep, Trivy, gitleaks, SAST pipelines

---

## Background

- **17 years** manufacturing operations (Toyota Production System)
- **Self-taught** software engineer
- **Focus:** The boring infrastructure that makes AI actually work in production

---

## Connect

Portland, OR · [LinkedIn](https://linkedin.com/in/james-young-3b77b3120) · jamesyng79@gmail.com

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/aretedriver)
