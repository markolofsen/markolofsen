# 👋 Mark K. (Igor Korotin)

**Principal Product Architect / Technical CPO — applied-AI systems & developer platforms**

I build platforms that replace teams. 20+ years turning hard technical domains — agentic AI, payments infrastructure, developer tooling — into production systems, usually shipping solo or with a small senior team, then scaling them. My focus now: making LLM agents reliable enough to run in production, and the developer platforms around them.

🌐 [cmdop.com](https://cmdop.com) · [djangocfg.com](https://djangocfg.com) · [linkedin.com/in/cmdop](https://linkedin.com/in/cmdop) · 📧 markolofsen@gmail.com

---

## 🧠 What I'm known for: making AI agents safe to run on real infrastructure

Letting agents act on live systems is easy to demo and dangerous in production — a plausible-looking action can break things. The hard part isn't the LLM; it's making agent actions **trustworthy at scale**. That problem is what I build around.

---

## 🚀 Flagship projects

### [Cmdop](https://cmdop.com) — AI agent & automation platform
An **agent → gRPC → server → SDK** platform with a multi-agent runtime: agent-to-agent handoff, tool-calling governed by structured-output contracts, and human-in-the-loop control. Every tool call runs through an **eval/instrumentation loop** — the contract is validated before execution, the full trace is logged, runs are scored on tool-call validity / task success / unintended side-effects, and brittle steps get guardrails + automatic retry/failover. That loop is what turns "a demo that works once" into a runtime you can trust to widen agent autonomy. Drives thousands of concurrent agent sessions over persistent gRPC/WebSocket streams. Node.js / Python / React SDKs.

### [DjangoCFG](https://djangocfg.com) — AI-native Django framework
Replaces Django's settings model with a **type-safe Pydantic v2 system** and unifies Django + Next.js admin + payments + realtime into one architecture. It's **AI-native**: capabilities are exposed through an **MCP server**, so coding agents query what the framework can do and its schemas directly instead of scraping docs. Compresses first-deploy SaaS setup from weeks to ~30 seconds.

### Earlier proof
A **crypto exchange engine** (sub-50ms order matching, multi-asset wallets/ledgers) · an **AI real-estate ROI platform** for a Top-3 Canadian firm (~50% faster assessments, ~$150K/yr saved, ~40% more qualified leads) · an **AI Cloud IDE** (VS Code in browser, AI agents, MCP) · an **Unreal Engine 5 Pixel Streaming** framework.

---

## 📦 Open source

| Project | What it is |
|---------|-----------|
| **[openrouter-commit](https://github.com/markolofsen/openrouter-commit)** ⭐ | AI commit-message generator, 300+ LLM models |
| **[django-cfg](https://github.com/markolofsen/django-cfg)** ⭐ | Type-safe Django config (Pydantic v2) |
| **[litellm2](https://github.com/markolofsen/litellm2)** | LLM orchestration wrapper |
| **[carapis-parsers](https://github.com/markolofsen)** | High-performance automotive data parsers, 20+ platforms |
| **[metaeditor](https://github.com/markolofsen/metaeditor)** | React toolkit for Unreal Engine 5 Pixel Streaming |
| **[docusaurus-doctor](https://github.com/markolofsen/docusaurus-doctor)** | Diagnostic CLI for Docusaurus |

15+ open-source libraries total — API client generators, automation CLIs, dev tooling.

---

## 🛠️ Stack

**Applied AI** — LLM orchestration · agents / multi-agent runtimes · MCP · RAG · structured outputs · LLM evals & observability · HITL
**Platform & distributed systems** — gRPC · WebSockets · high-load real-time · durable execution · idempotency/consistency · SDK & API design
**Full-stack** — Python · Django · FastAPI · Pydantic v2 · Next.js · React · TypeScript · Node.js · Go · PostgreSQL · Redis · ClickHouse
**Cloud** — AWS · GCP · Azure · Docker · Kubernetes · Cloudflare
**FinTech / other** — exchange & trading systems · ledgers · Ethereum/TRON/DeFi · Unreal Engine 5 / WebRTC

---

## 📊 GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=markolofsen&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=markolofsen&theme=dark&hide_border=false&layout=compact)

---

**Currently:** building applied-AI platforms (Cmdop, DjangoCFG) — agentic systems made reliable enough for production.
**Open to:** Principal Product Architect / Head of Applied AI / Technical CPO / VP Engineering roles, and fractional / advisory engagements. Remote (APAC, UTC+8; strong EMEA overlap), open to relocation.
