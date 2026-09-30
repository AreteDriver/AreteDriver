# James C. Young

**AI operations, enablement, and workflow tooling**

I build practical AI operations and workflow tools shaped by enterprise support, Lean operations, and frontline implementation. My public work focuses on cost visibility, evaluation, governance, MCP operations, documentation, and reliable handoffs between people and AI systems.

I am pursuing hands-on mid-level roles in **AI implementation, enablement, technical operations, solutions, workflow automation, process engineering, and business systems** in Oregon, Washington, or U.S.-remote teams.

## AI integration and developer operations

### [MCP Manager](https://github.com/AreteDriver/mcp-manager)

**Problem:** AI development clients store and interpret MCP configuration differently.

**Approach:** A project configuration, client-specific adapters, diagnostics and controlled writeback.

**Artifact and evidence:** [Source and quickstart](https://github.com/AreteDriver/mcp-manager#30-second-quickstart), [tests](https://github.com/AreteDriver/mcp-manager/tree/main/tests), and [workflow results](https://github.com/AreteDriver/mcp-manager/actions).

**Result boundary:** Implements configuration management and protocol diagnostics. Third-party server behavior and real-client compatibility need their own acceptance checks.

## Workflow governance

### [agent-lint](https://github.com/AreteDriver/agent-lint)

**Problem:** Workflow configurations can omit budgets, retry limits and output contracts.

**Approach:** Static rules produce findings that can be reviewed in a CLI or CI workflow.

**Artifact and evidence:** [Usage](https://github.com/AreteDriver/agent-lint#usage), [rule implementation](https://github.com/AreteDriver/agent-lint/tree/main/src/agent_lint/rules), and [annotated benchmark fixtures](https://github.com/AreteDriver/agent-lint/tree/main/tests/fixtures/benchmarks).

**Result boundary:** Configuration findings are review aids, not runtime enforcement or proof of savings. The project uses [BUSL-1.1](https://github.com/AreteDriver/agent-lint/blob/main/LICENSE).

## Evaluation and cost visibility

### [Arete Evals](https://github.com/AreteDriver/arete-evals)

**Problem:** An evaluation can report failures because its own metric is wrong.

**Approach:** Keep the original responses, diagnose the false positives, and replay corrected checks against the same data.

**Artifact and evidence:** [Case study](https://github.com/AreteDriver/arete-evals#case-study-the-first-live-run-of-benchgoblins-ask), [stored record](https://github.com/AreteDriver/arete-evals/blob/main/results/benchgoblins-ask-6ea664d3.json), and [offline verifier](https://github.com/AreteDriver/arete-evals/blob/main/scripts/verify_fix.py).

**Result boundary:** The replay tests the stored regression case. It does not establish current model quality or general detection accuracy.

### [ai-spend](https://github.com/AreteDriver/ai-spend)

**Problem:** Usage and cost information is scattered across providers.

**Approach:** A local CLI brings provider usage into a common reporting workflow.

**Artifact and evidence:** [Provider adapters](https://github.com/AreteDriver/ai-spend/tree/main/src/ai_spend/providers), [tests](https://github.com/AreteDriver/ai-spend/tree/main/tests), and the repository's demo.

**Result boundary:** Cost visibility is distinct from cost reduction; no savings are claimed without a measured comparison.

## Process, implementation and human handoffs

### [The Human Stack](https://github.com/AreteDriver/the-human-stack)

A practical reference for approaching AI work as an operational system: distinguish a hypothesis from implementation, define evidence, and make handoffs and limitations explicit. It supports the engineering case studies; it does not substitute for observed adoption or business outcomes.

## The operations-to-AI bridge

- **Frontline implementation:** process discovery, requirements translation, troubleshooting, standard work, SOPs, training, and adoption.
- **Operational improvement:** at Toyota Logistics Services, built an internal GPT and low-code workflow connecting scheduling, parts, and production work; combined with root-cause analysis and standard work, this helped reduce downtime 15% and move missing-parts incidents from a 15% baseline to zero.
- **Enterprise support:** at IBM, achieved greater than 95% first-time tier-two resolution and helped reduce escalations 20%.
- **Public engineering practice:** Python, SQL, FastAPI, Pydantic, REST APIs, PostgreSQL, SQLite, Docker, GitHub Actions, pytest, Playwright, MCP, and OpenAI and Claude APIs.

## How I approach implementation

1. Understand the user, workflow, constraints, and failure modes.
2. Translate the work into requirements, controls, and measurable outcomes.
3. Build the smallest useful implementation and test the risky paths.
4. Document the system, train the people using it, and make handoffs explicit.
5. Observe results and improve the workflow using evidence.

My public repositories are independent, production-minded projects. They demonstrate how I build and reason; they are not presented as employer production deployments or enterprise customer implementations.

## Current focus

I am especially interested in work that combines technical problem solving with implementation, support, evaluation, governance, integrations, documentation, training, and adoption. The best fit gives me direct exposure to production AI work while keeping me close to users and daily operations.

## Contact

[LinkedIn](https://www.linkedin.com/in/james-y-3b77b3120) · [Portfolio](https://github.com/AreteDriver/arete-portfolio) · [Writing](https://aretedriver.substack.com) · Portland, Oregon
