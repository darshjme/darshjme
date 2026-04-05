<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a0a0a,100:1a0000&height=200&section=header&text=Darshankumar%20Joshi&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=%E0%A4%95%E0%A4%B0%E0%A5%8D%E0%A4%AE%E0%A4%A3%E0%A5%8D%E0%A4%AF%E0%A5%87%E0%A4%B5%E0%A4%BE%E0%A4%A7%E0%A4%BF%E0%A4%95%E0%A4%BE%E0%A4%B0%E0%A4%B8%E0%A5%8D%E0%A4%A4%E0%A5%87%20%E0%A4%AE%E0%A4%BE%20%E0%A4%AB%E0%A4%B2%E0%A5%87%E0%A4%B7%E0%A5%81%20%E0%A4%95%E0%A4%A6%E0%A4%BE%E0%A4%9A%E0%A4%A8&descAlignY=58&descSize=16&descColor=cc9933" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=3000&pause=800&color=CC9933&center=true&vCenter=true&width=750&lines=Founder+of+DarshanDB+%E2%80%94+self-hosted+BaaS+in+Rust;Navsari+%E2%86%92+London+%E2%86%92+Dubai+%E2%86%92+Ahmedabad;Build+something+permanent.+Build+something+that+serves.)](https://git.io/typing-svg)

<a href="https://darshj.ai"><img src="https://img.shields.io/badge/darshj.ai-cc9933?style=flat-square&logoColor=000" /></a>
<a href="https://darshj.me"><img src="https://img.shields.io/badge/darshj.me-cc9933?style=flat-square&logoColor=000" /></a>
<a href="https://twitter.com/thedarshanjoshi"><img src="https://img.shields.io/badge/@thedarshanjoshi-e6edf3?style=flat-square&logo=x&logoColor=000" /></a>
<a href="https://linkedin.com/in/thedarshanjoshi"><img src="https://img.shields.io/badge/linkedin-e6edf3?style=flat-square&logo=linkedin&logoColor=0A66C2" /></a>
<a href="mailto:darshjme@gmail.com"><img src="https://img.shields.io/badge/darshjme@gmail.com-e6edf3?style=flat-square&logo=gmail&logoColor=EA4335" /></a>

</div>

---

> *"Sreyaan sva-dharmo vigunah para-dharmaat su-anushthitaat"*
> Better to walk your own path imperfectly than another's path perfectly. — Bhagavad Gita 3.35

I grew up in Navsari, a small town in southern Gujarat where Parsi fire temples stand next to Hindu mandirs and the chai tastes like monsoon rain. My father would say *"darshan karo"* every morning — see clearly. That word followed me across three countries and became the name of what I'm building now.

London for studies — Business Computing at Greenwich, Advanced Diploma at Sunderland. Dubai for production — VFX pipelines for Aquaman, The Invisible Man, The Last of Us Part II. Back to India, Ahmedabad, to build companies: GraymatterOnline (2015), Graymatter International (2018), Coeus Digital Media (2020), KnowAI (2024).

Four companies across a decade. Every one hit the same wall: the backend. Three weeks of plumbing before writing a single line of business logic. So I built the tool I always needed.

---

## DarshanDB

<a href="https://github.com/darshjme/darshandb">
  <img src="https://img.shields.io/badge/DarshanDB-F59E0B?style=for-the-badge&logo=rust&logoColor=000" />
</a>
<a href="https://github.com/darshjme/darshandb">
  <img src="https://img.shields.io/badge/Status-Alpha-orange?style=for-the-badge" />
</a>
<a href="https://github.com/darshjme/darshandb">
  <img src="https://img.shields.io/badge/Tests-731_passing-86efac?style=for-the-badge" />
</a>

A self-hosted Backend-as-a-Service built in Rust. Triple-store architecture over PostgreSQL. One binary that gives you a database, real-time sync, authentication, row-level permissions, and an admin dashboard. SDKs for React, Angular, Next.js, PHP, and Python.

```mermaid
graph TB
    subgraph DarshanDB["DarshanDB — Single Rust Binary"]
        API["REST + WebSocket"]
        AUTH["Auth\nArgon2id + JWT"]
        PERM["Permissions\nRow-Level Security"]
        QE["Query Engine\nDarshanQL"]
        TS["Triple Store\nEAV over Postgres"]
        SYNC["Real-Time Sync\nMutation → Diff → Push"]
    end

    subgraph SDKs["Connect from anywhere"]
        React["React"]
        Next["Next.js"]
        Angular["Angular"]
        PHP["PHP"]
        Python["Python"]
    end

    DarshanDB --> SDKs

    style DarshanDB fill:#1a1a2e,stroke:#F59E0B,color:#fff
    style SDKs fill:#0f3460,stroke:#F59E0B,color:#fff
```

**446 Rust tests. 92 TypeScript. 141 Python. 52 PHP. Auth, permissions, queries, and real-time — working end-to-end.**

**[github.com/darshjme/darshandb](https://github.com/darshjme/darshandb)**

---

## Companies

| Company | Role | Since |
|---------|------|-------|
| **[KnowAI](https://knowai.biz)** | Co-Founder & CTO | 2024 |
| **Coeus Digital Media LLC** | Founder & CTO | 2020 |
| **Graymatter International Inc** | Founder & MD | 2018 |
| **[GraymatterOnline LLP](https://graymatteronline.com)** | Founder & CEO | 2015 |

---

## Stack

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000" />
  <img src="https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=000" />
</p>

---

## Credentials

**Ph.D.** Business Computing Science | **CCNA** | **MCSE** | **CEH**

University of Greenwich | University of Sunderland

**VFX production:** Aquaman | The Invisible Man | The Last of Us Part II

---

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=darshjme&show_icons=true&bg_color=0d1117&title_color=cc9933&text_color=e6edf3&icon_color=cc9933&border_color=30363d&count_private=true" />
</p>

---

<p align="center"><sub>Navsari | London | Dubai | Ahmedabad</sub></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0000,50:0d1117,100:0d1117&height=120&section=footer" width="100%" />
