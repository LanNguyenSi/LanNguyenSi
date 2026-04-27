<h2 align="center">Hey, I'm Lan</h2>
<p align="center">Software Architect · Agentic AI Infrastructure · GovTech · Open Source</p>

<p align="center">
 <a href="https://lan-nguyen-si.de">Website</a> ·
 <a href="https://www.linkedin.com/in/lan-nguyen-si/">LinkedIn</a>
</p>

I architect GovTech platforms at **publicplan**. In parallel I build an open-source ecosystem that lets AI agents plan, build, validate, deploy, and monitor software alongside humans — focused on trustworthy autonomy through claim gates, grounding, and human-in-the-loop patterns.

## Start here

Pick the entry point that matches what you want to do — every repo below has a try-block at the top of its own README.

| If you want to… | Start with | Live |
|---|---|---|
| Run AI agents on tasks with a real audit trail | [agent-tasks](https://github.com/LanNguyenSi/agent-tasks) + [agent-tasks-cli](https://github.com/LanNguyenSi/agent-tasks-cli) | [agent-tasks.opentriologue.ai](https://agent-tasks.opentriologue.ai) |
| Track CVEs, licenses, and dep health across your repos | [depsight](https://github.com/LanNguyenSi/depsight) | |
| Deploy AI-managed services on a VPS | [deploy-panel](https://github.com/LanNguyenSi/deploy-panel) + [agent-relay](https://github.com/LanNguyenSi/agent-relay) | [deploy-panel.opentriologue.ai](https://deploy-panel.opentriologue.ai) |
| Search across all your local repos semantically (MCP) | [codebase-oracle](https://github.com/LanNguyenSi/codebase-oracle) | |
| Stop AI agents from acting on assumptions | [agent-grounding](https://github.com/LanNguyenSi/agent-grounding) | |
| Bootstrap a new agent project from a blueprint | [project-forge](https://github.com/LanNguyenSi/project-forge) + [scaffoldkit](https://github.com/LanNguyenSi/scaffoldkit) | [project-forge.opentriologue.ai](https://project-forge.opentriologue.ai) |
| Persist AI memory across sessions and machines | [agent-memory](https://github.com/LanNguyenSi/agent-memory) | |
| Monitor an agent fleet's health | [agent-ops-dashboard](https://github.com/LanNguyenSi/agent-ops-dashboard) | [ops.opentriologue.ai](https://ops.opentriologue.ai) |

## Names you'll see, briefly

- **Project OS** — the lifecycle umbrella. The repos above (agent-tasks, deploy-panel, project-forge, etc.) are its modules.
- **Triologue** — the human ↔ agent ↔ agent collaboration layer that runs on top.
- **opentriologue.ai** — the hosted demo instances of the modules. Self-host any of them via Docker.

## All product lines

### [Project OS](https://github.com/LanNguyenSi/project-os) · Human-Agent Dev Lifecycle

The full pipeline from idea to production, built for teams that work with AI agents.

| Module | What it does |
|--------|-------------|
| [agent-tasks](https://github.com/LanNguyenSi/agent-tasks) | Task workflow for humans + agents |
| [agent-tasks-cli](https://github.com/LanNguyenSi/agent-tasks-cli) | CLI client for agent-tasks |
| [deploy-panel](https://github.com/LanNguyenSi/deploy-panel) | Deployment management with API, MCP, GitHub Action |
| [agent-relay](https://github.com/LanNguyenSi/agent-relay) | Controlled execution on VPS targets |
| [agent-ops-dashboard](https://github.com/LanNguyenSi/agent-ops-dashboard) | Agent health monitoring |
| [project-forge](https://github.com/LanNguyenSi/project-forge) | Project scaffolding |
| [scaffoldkit](https://github.com/LanNguyenSi/scaffoldkit) | Declarative blueprint engine for project-forge |
| [agent-planforge](https://github.com/LanNguyenSi/agent-planforge) | Architecture planning + backlog generation |
| [agent-preflight](https://github.com/LanNguyenSi/agent-preflight) | Pre-push validation |

### [Agent Grounding](https://github.com/LanNguyenSi/agent-grounding) · Verification & Debugging

Prevents agents from acting on assumptions. 8 packages for runtime checks, claim validation, evidence tracking, and guided debugging.

### [Codebase Oracle](https://github.com/LanNguyenSi/codebase-oracle) · Semantic Code Search

Local-first MCP server that semantically indexes your repos. Ask questions across all of them at once.

### [Repo Intelligence](https://github.com/LanNguyenSi/repo-intelligence) · CI & Repo Health

CI insights, repo health scoring, and performance drift detection. [depsight](https://github.com/LanNguyenSi/depsight) is the standalone flagship for dependency health and CVE tracking.

### [Agent Memory](https://github.com/LanNguyenSi/agent-memory) · Persistent Memory

Sync, weave, and digest agent memories across sessions and environments.

### [Agent DX](https://github.com/LanNguyenSi/agent-dx) · Developer Experience

Playbooks and tooling for teams building with AI agents.

### [Dev Tools](https://github.com/LanNguyenSi/dev-tools) · CLI Utilities

Release preparation and batch Git operations.

## Standalone projects

- **[Telerithm](https://github.com/LanNguyenSi/telerithm)** — AI-powered log analytics for self-hosted teams
- **[Triologue](https://opentriologue.ai)** — real-time AI ↔ AI ↔ Human collaboration platform
- **[Depsight](https://github.com/LanNguyenSi/depsight)** — dependency health dashboard, CVE tracking, security scoring
- **[Clawd Monitor](https://github.com/LanNguyenSi/clawd-monitor)** — monitoring dashboard for OpenClaw

## Stack

TypeScript · Next.js · Hono · Node.js · PostgreSQL · Prisma · Docker · Traefik · Symfony

---

*Architecting trustworthy AI agents, in public.*
