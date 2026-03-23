# Darshankumar Joshi

Building production-grade tooling for LLM agents.

![GitHub followers](https://img.shields.io/github/followers/darshjme?style=flat-square&color=58a6ff) ![GitHub stars](https://img.shields.io/github/stars/darshjme?style=flat-square&color=f78166)

---

## Production Agent Toolkit

A suite of four composable libraries for building reliable LLM agent systems.

```
┌─────────────────────────────────────────────────────────────┐
│                   production-agent-toolkit                   │
│                                                             │
│  ┌───────────┐    ┌──────────────────┐    ┌─────────────┐  │
│  │ llm-router│───▶│react-guard-patt..│───▶│agent-memory │  │
│  │           │    │                  │    │             │  │
│  │  Route    │    │  Guard during    │    │  Remember   │  │
│  │  first    │    │  execution       │    │  always     │  │
│  └───────────┘    └──────────────────┘    └──────┬──────┘  │
│                                                   │         │
│                                          ┌────────▼──────┐  │
│                                          │  agent-evals  │  │
│                                          │               │  │
│                                          │  Evaluate     │  │
│                                          │  after        │  │
│                                          └───────────────┘  │
└─────────────────────────────────────────────────────────────┘

Route first. Guard during. Remember always. Evaluate after.
```

| Library | What it does | Tests |
|---------|-------------|-------|
| [agent-evals](https://github.com/darshjme/agent-evals) | 3D evaluation framework for LLM agent outputs | 45 |
| [react-guard-patterns](https://github.com/darshjme/react-guard-patterns) | Stop-condition guards for agentic loops | 14 |
| [llm-router](https://github.com/darshjme/llm-router) | Semantic task routing across LLM providers | 10 |
| [agent-memory](https://github.com/darshjme/agent-memory) | Short-term + episodic memory for agents | 13 |

**82 tests total** across the toolkit. → [production-agent-toolkit](https://github.com/darshjme/production-agent-toolkit)

---

## Other Projects

- **[brahmand](https://github.com/darshjme/brahmand)** — Universal LLM terminal interface
- **[samast](https://github.com/darshjme/samast)** — LLM integration framework

---

## Find me

[@thedarshanjoshi](https://twitter.com/thedarshanjoshi) on X
