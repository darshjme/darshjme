<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a0a0a,100:1a0000&height=200&section=header&text=Darshankumar%20Joshi&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=कर्मण्येवाधिकारस्ते%20मा%20फलेषु%20कदाचन&descAlignY=58&descSize=16&descColor=cc9933" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=800&color=CC9933&center=true&vCenter=true&width=750&lines=Creator+of+DarshanDB+%E2%80%94+the+open-source+BaaS+built+in+Rust;Vipra+who+writes+code.+Brahmin+who+builds+systems.;Gujarat+%E2%86%92+the+world.+Dharma+%E2%86%92+execution.)](https://git.io/typing-svg)

<a href="https://darshj.me"><img src="https://img.shields.io/badge/darshj.me-cc9933?style=flat-square&logoColor=000" /></a>
<a href="https://twitter.com/thedarshanjoshi"><img src="https://img.shields.io/badge/@thedarshanjoshi-e6edf3?style=flat-square&logo=x&logoColor=000" /></a>
<a href="https://linkedin.com/in/thedarshanjoshi"><img src="https://img.shields.io/badge/linkedin-e6edf3?style=flat-square&logo=linkedin&logoColor=0A66C2" /></a>

</div>

---

> *"Sreyaan sva-dharmo vigunah para-dharmaat su-anushthitaat"*
> Better to walk your own path imperfectly than another's path perfectly. — Bhagavad Gita 3.35

I am a Brahmin from Gujarat. My ancestors built temples. I build systems.

The Sompura Brahmins of my land carved stone into structures that outlasted empires. The tools changed — chisel became compiler, sandstone became silicon — but the intent is the same: **build something permanent. Build something that serves.**

Vyasa compiled the Vedas so knowledge wouldn't scatter. I write open-source so tools don't stay locked. Same dharma. Different medium.

Founded my first company in 2015. Currently running three across AI, media, and enterprise — Coeus Digital Media, Graymatter International, and KnowAI. Before this: VFX for Aquaman, The Invisible Man, The Last of Us Part II. India's first NFT-funded film. Ph.D. Business CS. CCNA. MCSE. CEH.

---

## DarshanDB — The Self-Hosted Backend-as-a-Service

<a href="https://github.com/darshjme/darshandb">
  <img src="https://img.shields.io/badge/DarshanDB-F59E0B?style=for-the-badge&logo=rust&logoColor=000" />
</a>

**One binary. Every framework. Zero loopholes.** Built from scratch in Rust.

I got tired of spending three weeks on backend plumbing before writing business logic. Firebase is NoSQL spaghetti. Supabase is REST with real-time bolted on. InstantDB is cloud-only. Convex is a black box. So I built what I actually wanted.

```mermaid
graph LR
    subgraph DarshanDB["DarshanDB — What's Inside"]
        TS["Triple Store<br/><i>EAV over Postgres</i>"]
        QE["Query Engine<br/><i>DarshanQL</i>"]
        RT["Real-Time Sync<br/><i>WebSocket + MsgPack</i>"]
        AU["Auth Engine<br/><i>JWT + OAuth + MFA</i>"]
        FN["Function Runtime<br/><i>V8 Sandboxed</i>"]
        PM["Permissions<br/><i>Zero-Trust RLS</i>"]
        ST["Storage<br/><i>S3-compatible</i>"]
    end

    subgraph SDKs["SDKs"]
        React["React"]
        Next["Next.js"]
        Angular["Angular"]
        Vue["Vue"]
        PHP["PHP"]
        Python["Python"]
    end

    DarshanDB --> SDKs

    style DarshanDB fill:#1a1a2e,stroke:#F59E0B,color:#fff
    style SDKs fill:#0f3460,stroke:#F59E0B,color:#fff
```

| What | Details |
|------|---------|
| **Core** | Rust (Axum + Tokio), PostgreSQL 16+ with pgvector |
| **Protocol** | MsgPack over WebSocket — 206x faster than REST polling |
| **Security** | 11-layer defense-in-depth, OWASP Top 10 eliminated |
| **SDKs** | React, Next.js, Angular, Vue, Svelte, PHP, Python, Vanilla JS |
| **Deploy** | Single ~30MB binary, Docker, or Kubernetes Helm chart |

**[github.com/darshjme/darshandb](https://github.com/darshjme/darshandb)**

---

## How I Build

```mermaid
flowchart TD
    D[Dharma\nWhat must be built?] --> V[Vichara\nThink from first principles]
    V --> K[Karma\nWrite the code. Ship the thing.]
    K --> S[Seva\nOpen-source it. Serve others.]
    S --> L[Loka\nThe world builds on top]
    L --> D

    style D fill:#cc9933,color:#000
    style V fill:#1a1a2e,color:#fff
    style K fill:#0d1117,color:#fff
    style S fill:#1a3320,color:#fff
    style L fill:#1e3a5f,color:#fff
```

---

## Other Work

**Mohini** — An autonomous agent OS written from scratch in Rust. 14 crates. Named after the enchantress form of Vishnu. She routes, remembers, guards, evaluates. She never sleeps.

**KnowAI** — AI-native enterprise platform. React 19, Next.js 15, PostgreSQL. 60+ autonomous agents managing Slack, ClickUp, Miro, and hiring.

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
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

Ph.D. Business CS | Hons Business Computing (Greenwich) | Advanced Diploma IT (Sunderland) | CCNA | MCSE | CEH

---

<p align="center">
  <img src="https://img.shields.io/badge/Business%20Standard-1A1A2E?style=flat-square" />
  <img src="https://img.shields.io/badge/TechBullion-0066CC?style=flat-square" />
  <img src="https://img.shields.io/badge/Film%20Daily-222?style=flat-square" />
  <img src="https://img.shields.io/badge/Amazon%20Prime%20Video-00A8E0?style=flat-square&logo=primevideo&logoColor=white" />
</p>

---

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=darshjme&show_icons=true&bg_color=0d1117&title_color=cc9933&text_color=e6edf3&icon_color=cc9933&border_color=30363d&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=darshjme&layout=compact&bg_color=0d1117&title_color=cc9933&text_color=e6edf3&border_color=30363d&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=darshjme&theme=github-dark-blue&border=30363d&stroke=30363d&ring=cc9933&fire=cc9933&currStreakLabel=cc9933&background=0d1117" />
</p>

---

<p align="center"><sub>Gujarat | India | Dubai | USA</sub></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0000,50:0d1117,100:0d1117&height=120&section=footer" width="100%" />
