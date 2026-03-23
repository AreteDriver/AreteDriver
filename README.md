# James C. Young — AreteDriver

**AI Enablement Engineer | Operational Intelligence | DevTools**
Python · Rust · TypeScript · Linux Systems · Full CI/CD

I apply lean manufacturing systems thinking to AI and software engineering.
17 years in enterprise operations (Toyota, IBM) before I touched a model.
The result: systems that ship reliably, not just demo well.

---

## What I Build

**AI workflow orchestration** — multi-agent pipelines with cost tracking, checkpointing, and structured feedback loops
**Document intelligence** — investigative-grade ingestion, entity extraction, and co-occurrence analysis
**Developer tooling** — CLI utilities for AI teams: spend tracking, agent auditing, context generation
**Production AI applications** — autonomous content pipelines running at scale across multiple languages

---

## Featured Projects

### [Animus](https://github.com/AreteDriver/Animus) — Multi-Agent Orchestration Framework
Coordinate specialized AI agents across enterprise workflows with budget controls, quality gates, and checkpoint/resume.
FastAPI backend · React dashboard · 4 packages (Core/Forge/Quorum/Bootstrap) · 37 tools · Quorum coordination protocol ([PyPI](https://pypi.org/project/convergentAI/)) · 14,596+ tests · 97% coverage

### [BenchGoblins](https://benchgoblins.com) — AI Fantasy Sports Decision Engine
League-centric start/sit, trade analysis, and matchup projections. Grok-primary scored LLM routing with Goblin Verdict. Live on Fly.io + Vercel.
Next.js · FastAPI · PostgreSQL · Redis · Stripe · 2,647 tests · 98% coverage

### [EVE Gatekeeper](https://github.com/AreteDriver/EVE_Gatekeeper) — EVE Online Route Intelligence
SSO-authenticated route planner with 14-layer interactive map, gate camp warnings, expandable risk breakdowns, and Stripe billing. Live on Fly.io + Vercel.
Next.js · FastAPI · SQLite · Stripe · 3,177+ tests · [edengk.com](https://edengk.com)

### [DOSSIER](https://github.com/AreteDriver/DOSSIER) — Document Intelligence Platform
Investigative-grade document analysis: ingest PDFs/emails/scans, extract named entities, surface co-occurrence relationships.
SQLite FTS5 · Custom NER (4 entity types) · Auto-classification · 1,084 tests · 97% coverage

### [agent-lint](https://github.com/AreteDriver/agent-lint) — Agent Workflow Auditor
CLI tool for cost estimation and anti-pattern detection in agent workflow YAML configs. [PyPI](https://pypi.org/project/agentlinter/)
Static analysis · 17 lint rules · CI integration · Zero LLM dependency · 296 tests · 98% coverage

### [Argus Overview](https://github.com/AreteDriver/Argus_Overview) — Linux Multi-Window Manager for EVE Online
Real-time 30 FPS window previews, team management, auto-tiling layouts, EVE settings sync.
2,500+ downloads · 2,179 tests · 100% coverage · [PyPI](https://pypi.org/project/argus-overview/)

---

## EVE Frontier Intelligence Suite

### [WatchTower / Witness](https://github.com/AreteDriver/witness) — On-Chain Intelligence & Dossier NFTs
Discord bot with 16 commands, Dossier NFT minting (3 tiers on Sui testnet), Oracle Loop for on-chain entity profiling, reputation cache, Stripe + SUI payments.
FastAPI · Sui Move · Discord.py · dApp Kit · 774 tests

### [Monolith](https://github.com/AreteDriver/monolith) — EVE Frontier Anomaly Detection
35 detection rules, 17 checkers, item ledger, chain state verification via Sui GraphQL, public API v1, webhook subscriptions, Canvas2D heatmap with 24K systems.
FastAPI · SQLite · Sui GraphQL · 312 tests · [anchormd 100/100](https://anchormd.dev)

### [Frontier Tribe OS](https://github.com/AreteDriver/frontier-tribe-os) — Corp Management Dashboard
7 modules: Kill Feed, LLM Briefing, System Intelligence, Alert Config, Pilot/Corp Intel, Battle Reports, Signature Resolution. Live on Fly.io + Vercel.

---

## Dev Tools

| Tool | What | Tests |
|------|------|------:|
| [anchormd](https://github.com/Arete-Consortium/anchormd) | AI agent context file generator/auditor + tech debt scanner ([PyPI](https://pypi.org/project/anchormd/), [anchormd.dev](https://anchormd.dev)) | 693 |
| [promptctl](https://github.com/AreteDriver/promptctl) | Claude API toolkit — prompt engineering, code review, doc intelligence ([PyPI](https://pypi.org/project/promptctlai/)) | 330 |
| [context-hygiene](https://github.com/AreteDriver/context-hygiene) | Context window optimization — detect bloat, measure signal density ([PyPI](https://pypi.org/project/context-hygiene/)) | 398 |
| [memboot](https://github.com/AreteDriver/memboot) | Zero-infra persistent memory for LLMs — SQLite + TF-IDF ([PyPI](https://pypi.org/project/memboot/)) | 304 |
| [ai-spend](https://github.com/AreteDriver/ai-spend) | AI API cost aggregator — Anthropic + OpenAI billing in one view ([PyPI](https://pypi.org/project/ai-spend/)) | 267 |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | MCP server manager — discover, monitor, manage across IDEs ([PyPI](https://pypi.org/project/arete-mcp/)) | 158 |

---

## CI/CD & Infrastructure

**83 workflow files across 20+ repos. 0 open code scanning alerts. 0 dependabot alerts.**

| Capability | Evidence |
|---|---|
| Containerization | Multi-stage Dockerfiles, docker-compose, [templates](https://github.com/AreteDriver/ci-templates) |
| Kubernetes | Deployments, HPA, Ingress, Kustomize, Helm chart |
| CI Pipelines | Lint → test → SAST → build → deploy across Python, Rust, TypeScript |
| Security Scanning | CodeQL + gitleaks + Bandit + Semgrep + Trivy + pip-audit |
| Live Deployments | 9 services on Fly.io + Vercel (see Proof below) |
| PyPI Packages | 11 packages via OIDC trusted publishing |
| Benchmarks | Automated performance regression tracking on gh-pages (3 repos) |

---

## Proof

| Metric | |
|---|---|
| **Tests across active repos** | 40,000+ |
| **Projects with CI green** | 20+ |
| **Live deployments** | BenchGoblins, EVE Gatekeeper, WatchTower, Monolith, Frontier Tribe OS, anchormd + license server, AI Cards, StayCards |
| **PyPI packages** | anchormd, agent-lint, ai-spend, promptctl, context-hygiene, mcp-manager, memboot, argus-overview, convergentAI, G13-linux, LikX |
| **Security posture** | 0 code scanning alerts, 0 dependabot alerts across all repos |
| **Real users** | Argus Overview: 2,500+ downloads |

---

## Technical Stack

| Domain | Tools |
|---|---|
| Languages | Python, Rust, TypeScript |
| AI/ML | Claude API, OpenAI, Grok, Ollama, multi-agent orchestration |
| Backend | FastAPI, SQLite, PostgreSQL, Redis |
| Frontend | React, Next.js, React Native/Expo, PySide6 |
| Blockchain | Sui Move, GraphQL, dApp Kit |
| Infrastructure | Docker, Kubernetes, Helm, GitHub Actions, Fly.io, Vercel |
| Security | CodeQL, Bandit, Semgrep, Trivy, gitleaks, SAST pipelines |

---

## Engineering Philosophy

Operational reliability over algorithmic elegance.
A system that ships predictably beats a system that demos brilliantly.
Standard work, visual management, poka-yoke — applied to software.

---

[LinkedIn](https://linkedin.com/in/james-young-3b77b3120) · [Substack](https://substack.com/@aretedriver) · [Discord](https://discord.gg/fdzQkrt8) · Portland, OR
