<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Darshankumar%20Joshi&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Agentic%20AI%20%C2%B7%20Rust%20Systems%20%C2%B7%20Web3%20%C2%B7%20Entrepreneur&descAlignY=58&descSize=18&descColor=8b949e" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+the+world's+most+complete+agent+runtime+in+Rust.;Founder+%C2%B7+CTO+%C2%B7+CFO.+Three+companies.+Three+continents.;One+binary.+104+skills.+40+channels.+188+models.)](https://git.io/typing-svg)

<a href="https://darshj.me"><img src="https://img.shields.io/badge/darshj.me-e6edf3?style=flat-square" /></a>
<a href="https://twitter.com/thedarshanjoshi"><img src="https://img.shields.io/badge/@thedarshanjoshi-e6edf3?style=flat-square&logo=x&logoColor=000" /></a>
<a href="https://linkedin.com/in/thedarshanjoshi"><img src="https://img.shields.io/badge/linkedin-e6edf3?style=flat-square&logo=linkedin&logoColor=0A66C2" /></a>

</div>

---

I build autonomous systems in Rust and ship products across AI, crypto, and enterprise. Founded my first company in 2015. Currently running three — Coeus Digital Media, Graymatter International, and KnowAI.

Before all this, I did VFX for Aquaman, The Invisible Man, and The Last of Us Part II. Made India's first NFT-funded film. Studied at Greenwich and Sunderland. Hold a CCNA, MCSE, and CEH.

Most of my time now goes into **Mohini** — an agent OS written from scratch in Rust. 14 crates, 104 skills, 40 channels, 188 models. One binary.

---

## Production Agent Infrastructure

[![Arsenal](https://img.shields.io/badge/Arsenal-28%20libs%201226%20tests-blue)](https://github.com/darshjme/arsenal) [![1000+ Tests](https://img.shields.io/badge/🎯_1226_tests-milestone-gold)](https://github.com/darshjme/arsenal)

The complete production agent pipeline — 28 zero-dependency Python libraries: [arsenal →](https://github.com/darshjme/arsenal)

| Library | Description |
|---|---|
| [**agent-evals**](https://github.com/darshjme/agent-evals) | Evaluation framework for LLM agent outputs and behaviors |
| [**react-guard-patterns**](https://github.com/darshjme/react-guard-patterns) | ReAct loop guard patterns to prevent runaway agent execution |
| [**llm-router**](https://github.com/darshjme/llm-router) | Intelligent routing across LLM providers based on cost and capability |
| [**agent-memory**](https://github.com/darshjme/agent-memory) | Persistent and working memory primitives for stateful agents |
| [**agent-guardrails**](https://github.com/darshjme/agent-guardrails) | Input/output safety guardrails for production agent pipelines |
| [**agent-observability**](https://github.com/darshjme/agent-observability) | Structured tracing, logging, and metrics for agent systems |
| [**agent-budget**](https://github.com/darshjme/agent-budget) | Token and cost budgeting with hard limits and alerts |
| [**agent-context**](https://github.com/darshjme/agent-context) | Context window management and intelligent compression |
| [**agent-tools**](https://github.com/darshjme/agent-tools) | Tool registry, validation, and execution harness |
| [**agent-retry**](https://github.com/darshjme/agent-retry) | Retry logic with exponential backoff and circuit breakers |
| [**agent-state**](https://github.com/darshjme/agent-state) | Lightweight agent state machine with transition guards |
| [**agent-schema**](https://github.com/darshjme/agent-schema) | Schema validation for structured LLM outputs |
| [**agent-pipeline**](https://github.com/darshjme/agent-pipeline) | Composable pipeline orchestrator: Route→Budget→Guard→Remember→Compress→Observe→Evaluate→Validate→Retry→State→Schema |
| [**agent-cache**](https://github.com/darshjme/agent-cache) | Semantic and exact caching for LLM calls — cut costs by catching duplicate and similar prompts |
| [**agent-config**](https://github.com/darshjme/agent-config) | Secrets, env config, hot-reload — zero credential leaks with auto-redacting SecretStr |
| [**agent-events**](https://github.com/darshjme/agent-events) | Event bus, pub/sub, and history replay for multi-agent coordination |
| [**agent-health**](https://github.com/darshjme/agent-health) | Health checks and liveness monitoring — HTTP, disk, memory, latency probes in parallel |
| [**agent-rate-limiter**](https://github.com/darshjme/agent-rate-limiter) | Proactive rate limiting for LLM API calls — prevent 429 errors before they happen |
| [**agent-circuit-breaker**](https://github.com/darshjme/agent-circuit-breaker) | Circuit breaker pattern — CLOSED/OPEN/HALF_OPEN state machine, FallbackBreaker for cascade failure prevention |
| [**agent-validator**](https://github.com/darshjme/agent-validator) | Input validation, prompt injection detection, PII scanning — composable rule chains, zero dependencies |
| [**agent-logger**](https://github.com/darshjme/agent-logger) | Structured JSON logging, correlation IDs, auto-redaction, log sampling — trace every request end-to-end |
| [**agent-timer**](https://github.com/darshjme/agent-timer) | SLA enforcement, p50/p95/p99 tracking, @timed decorator, multi-step profiler — zero dependencies |
| [**agent-queue**](https://github.com/darshjme/agent-queue) | Priority task queue, deduplication, worker pool, backpressure — zero dependencies |
| [**agent-fallback**](https://github.com/darshjme/agent-fallback) | FallbackChain, ConditionalFallback, RetryThenFallback, @fallback decorator — zero dependencies |
| [**agent-semaphore**](https://github.com/darshjme/agent-semaphore) | Concurrency limiting, resource pool, throttled executor, @limit_concurrent — zero dependencies |
| [**agent-dependency**](https://github.com/darshjme/agent-dependency) | DI container, @inject decorator, scoped containers, ServiceLocator — zero dependencies |
| [**agent-context-window**](https://github.com/darshjme/agent-context-window) | Token counting, sliding window, content prioritization, truncation strategies — zero dependencies |

---

<p align="center">
  <img src="./assets/projects.svg" alt="Projects" width="100%">
</p>

**[Mohini](https://github.com/darshjme/mohini)** — Full agentic runtime. Persistent memory, WASM-sandboxed skills, shadow spawning, self-healing orchestration. The whole stack in Rust.

**[KnowAI ERP](https://github.com/darshjme/knowai-erp)** — AI-native enterprise platform. React 19, Next.js 15, PostgreSQL. Built for real operations, not demos.

**[MyCryptoCoin](https://github.com/darshjme/mycryptocoin)** — Multi-chain crypto payment gateway. One API, every chain. TypeScript.

**[WhatsApp 2FA](https://github.com/darshjme/whatsapp-2fa)** — Self-hosted OTP/2FA over WhatsApp. REST API, zero third-party dependency.


---

## How I Build

```mermaid
flowchart TD
    I[💡 Idea] --> D{Domain?}

    D -->|AI / Agents| A[Rust crate or Python lib]
    D -->|Product / SaaS| B[Next.js + PostgreSQL]
    D -->|Web3 / Crypto| C[TypeScript + multi-chain]

    A --> A1[herald · engram · sentinel\nverdict · agent-guardrails\nagent-observability]
    B --> B1[KnowAI ERP\nMyCryptoCoin\nWA2FA SaaS]
    C --> C1[MyCryptoCoin\nNFT infrastructure]

    A1 & B1 & C1 --> M[Mohini\nOrchestrates everything\n24/7 autonomous runtime]

    M --> S[Ship → GitHub → X.com]

    style I fill:#1f6feb,color:#fff
    style M fill:#6e2020,color:#fff
    style S fill:#1a4731,color:#fff
```

---

| Company | Role | Since |
|---|---|---|
| **KnowAI** | Co-Founder, CFO & CTO | 2024 |
| **Coeus Digital Media LLC** | Founder & CTO | 2020 |
| **Graymatter International Inc** | Founder & MD | 2018 |
| **GraymatterOnline LLP** | Founder & CEO | 2015 |

---

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000" />
  <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

Ph.D. Business CS · Hons Business Computing (Greenwich) · Advanced Diploma IT (Sunderland) · CCNA · MCSE · CEH

---

<p align="center">
  <img src="https://img.shields.io/badge/Business%20Standard-1A1A2E?style=flat-square" />
  <img src="https://img.shields.io/badge/TechBullion-0066CC?style=flat-square" />
  <img src="https://img.shields.io/badge/Film%20Daily-222?style=flat-square" />
  <img src="https://img.shields.io/badge/Amazon%20Prime%20Video-00A8E0?style=flat-square&logo=primevideo&logoColor=white" />
</p>

---

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=darshjme&show_icons=true&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=f78166&border_color=30363d&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=darshjme&layout=compact&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&border_color=30363d&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=darshjme&theme=github-dark-blue&border=30363d&stroke=30363d&ring=58a6ff&fire=f78166&currStreakLabel=58a6ff&background=0d1117" />
</p>

---

<p align="center"><sub>India · Dubai · USA</sub></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer" width="100%" />
