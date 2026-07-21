## Hi, I'm Dexter (not the serial killer) 👋

> I design and harden agentic AI workflows that fit inside real enterprise architectures — recruiting, CRM/support, travel, and resale — with explicit attention to identity, data boundaries, governance, and operational reality.

10+ years in Dynamics 365 CE, Power Platform, and Azure integration across healthcare, med-device, and B2B consulting. These days I build and ship production-pattern agentic AI systems on that same governance instinct — not demos, systems with real users, measured costs, and a human in the loop wherever it matters.

## What I'm Building


- 🎧 **[agentic-crm-support-architecture](https://github.com/tbalt88/agentic-crm-support-architecture)** — a production-pattern reference architecture for AI-assisted customer support: deterministic classification with confidence thresholds and rule-based fallback, guarded RAG with trust scoring against prompt injection, mandatory human approval on high-risk actions, full audit trail, optional transactional Postgres backend. 33 tests, fails safe (not silent) with no API key configured.
- 🔨 **Scanner** — live in production at [scanner.auctionit.io](https://scanner.auctionit.io) *(source private)*. Staff photograph an estate sale, the app groups multi-angle photos into items, identifies each one via reverse image search, and pulls market pricing evidence — but the human sets the final price on every item, not the model. FastAPI + React on Render, Postgres, Cloudflare R2. Phase 2A (multi-user admin, cost tracking) shipped as v1.2.0; measured cost: $1.15 for a 20-photo batch.
- 🛡️ **Zero to Hardened Agents** — [`zero-to-hardened-agents`](https://github.com/tbalt88/zero-to-hardened-agents): an 8-stage, run-it-yourself curriculum that I self made from a raw LLM call to a hardened, hybrid cloud/local multi-agent system — grounded RAG that refuses to hallucinate outside its sources, manual tool-calling, real vector search, a multi-agent DAG with a runaway-loop governor, a cloud/local hybrid router, and an automated adversarial test suite (prompt injection, RAG poisoning, PII containment) against the OWASP Top 10 for LLM Applications. Built as a real two-agent collaboration — Gemini planned the architecture, Claude Code wrote every line — with a full, reproducible handoff log.
- 🎯 **houndstooth** *(private)* — end-to-end job-hunt automation: a multi-source harvester (direct ATS APIs + job boards) → Claude-scored fit ranking → Claude-drafted, verified tailored resume/cover letter → Drive + email digest, running daily via GitHub Actions. My personal ATS and a reference pattern for recruiting-ops workflows.
- ✈️ **DexEvo Travel** — live (v2 in progress) at [travel.dexevo.io](https://travel.dexevo.io) *(source private)*. A structured, shareable trip itinerary that the traveler and an AI agent edit through the same API, instead of a one-off chat transcript.
- 🔌 **memory-bridge-mcp** *(private)* — a personal, cross-surface memory system exposed as a remote MCP server on Cloudflare Workers + D1, live-verified from claude.ai and Claude Code, GitHub OAuth-gated to one allowlisted account. It's the recall tier under **second-brain**, my Obsidian-based agent-agnostic knowledge system — together they let an AI agent keep working context across sessions and surfaces instead of starting from zero every time.

## How I Think

- **Architecture first** — identity, data boundaries, observability, and failure modes before "cool demos."
- **Hardened agents** — simplify/harden/document loops, mis-use mitigation, and OWASP LLM threat models baked into design, not bolted on after.
- **Human where it counts** — the AI proposes, a person decides on anything high-risk, high-cost, or irreversible. Every one of the projects above enforces that somewhere.
- **Leading agents like I led teams** — written manifests before any code gets touched, comprehension checks that block start until the agent proves it understood the ask (not just repeats it back), layered verification instead of one green checkmark, and defects that become permanent guardrails instead of one-off fixes. It's how agentic-crm-support-architecture, houndstooth, and Zero to Hardened Agents actually got built — same discipline I used running teams, aimed at agents now.

## Open To

- **Forward-Deployed Engineer / Forward-Deployed Architect** — embedded with a team, shipping and hardening real systems, not managing a roadmap from a distance.
- **Solutions Architect / Solutions Engineer** — healthcare, med-device, or other regulated verticals, hands-on and client-facing.
- **AI Enterprise Architect / AI Governance Architect** — individual-contributor track, bringing production governance patterns (see agentic-crm-support-architecture and Zero to Hardened Agents above) to regulated AI deployments.
- **Individual contributor, by choice** — I've led people before (4 direct + 20 matrixed engineers); these days I point that same leadership discipline at AI agents instead of a headcount. Not chasing people-management, director, or C-suite titles.

<!-- REPO-TRACKER:START -->
<!-- Auto-updated: Sun, 19 Jul 2026 08:08:21 GMT -->

## 📊 GitHub Dashboard

| Metric | Value |
|--------|-------|
| 📦 Public repos | 12 |
| ⭐ Total stars earned | 0 |
| 🍴 Forks maintained | 166 |
| 🗄 Archived | 0 |

> ⚡ **12 fork(s) have merge conflicts** — [view details](https://github.com/tbalt88/repo-tracker)

---

## 🏆 Top Repositories

| Repo | Description | Stars | Language |
|-o|-------------|-------|----------|
| [**ai-travel-funnel-and-booking**](https://github.com/tbalt88/ai-travel-funnel-and-booking) | AI-enabled travel workspace: a structured, shareable trip itinera… | ⭐ 0 | Python |
| [**second-brain**](https://github.com/tbalt88/second-brain) | Dexter Domingo's personal, agent-agnostic knowledge system: an Ob… | ⭐ 0 | Python |
| [**scroll-world**](https://github.com/tbalt88/scroll-world) | A skill that turn any brand into a scrollable 3D world | ⭐ 3,663 ↑ | JavaScript |
| [**houndstooth**](https://github.com/tbalt88/houndstooth) | Job-hunt automation, end to end: multi-source harvester → AI fit-… | ⭐ 0 | Python |
| [**agentic_coding_flywheel_setup**](https://github.com/tbalt88/agentic_coding_flywheel_setup) | Bootstraps a fresh Ubuntu VPS into a complete multi-agent AI deve… | ⭐ 1,551 ↑ | Shell |
| [**antigravity-awesome-skills**](https://github.com/tbalt88/antigravity-awesome-skills) | AAS Core preview is the local, agent-first control plane for disc… | ⭐ 43, 560 ↑ | Python |

> 📋 [See full repo index →](https://github.com/tbalt88/repo-tracker)

---

## 🛠 Top Languages

`Python` ×49  `TypeScript` ×33  `JavaScript` ×18  `Jupyter Notebook` �6  `C#` �6

---

## 🕐 Recently Updated

| Repo | Last Push | Stars |
|-o|-----------|-------|
| [crmtwenty](https://github.com/tbalt88/crmtwenty) | Sun Jul 19 2026 | ⭐ 0 |
| [wifi-densepose](https://github.com/tbalt88/wifi-densepose) | Sun Jul 19 2026 | ⭐ 0 |
| [ai-travel-funnel-and-booking](https://github.com/tbalt88/ai-travel-funnel-and-booking) | Sun Jul 19 2026 | ⭐ 0 |
| [second-brain](https://github.com/tbalt88/second-brain) | Sun Jul 19 2026 | ⭐ 0 |
| [houndstooth](https://github.com/tbalt88/houndstooth) | Sat Jul 18 2026 | ⭐ 0 |
---

<sub>🤖 Auto-updated daily by <a href="https://github.com/tbalt88/repo-tracker">repo-tracker</a></sub>
<!-- REPO-TRACKER:END -->

## GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/tbalt88)

<details>
<summary>A little about how I work</summary>

- "Ship beats perfect" — I build tools to solve my own problems, harden them, then share them.
- I keep a running technical watchlist by forking and auto-rebasing repos worth tracking — that's what the fork count above is, not shelved side projects.
- Run 3–6 agent instances concurrently when the problem calls for it. Also: gym enthusiast.

</details>
