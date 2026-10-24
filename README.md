# eddavv

**AI Architect & Engineer** — I design, build, and put AI systems *into production*.

AI-native by default: systems are built around the model, not models bolted onto legacy workflows.

## Status

![status: building](https://img.shields.io/badge/status-building-2ea043?style=flat-square&logo=github&logoColor=ffffff)
![local-first: yes](https://img.shields.io/badge/local--first-yes-3aa0c8?style=flat-square&logo=github&logoColor=ffffff)
![evals-first: yes](https://img.shields.io/badge/evals--first-yes-7f9cf5?style=flat-square&logo=github&logoColor=ffffff)

![airgap-capable](https://img.shields.io/badge/airgap--capable-6e7781?style=flat-square&logo=github&logoColor=9aa7b5)
![cost-bounded](https://img.shields.io/badge/cost--bounded-6e7781?style=flat-square&logo=github&logoColor=9aa7b5)
![no-vendor-lock](https://img.shields.io/badge/no--vendor--lock-6e7781?style=flat-square&logo=github&logoColor=9aa7b5)
![open-weights-friendly](https://img.shields.io/badge/open--weights-6e7781?style=flat-square&logo=github&logoColor=9aa7b5)

> **operational contract.** `local-first` + `evals-first` ⇒ nothing ships without a deterministic golden-set gate and a cost / latency budget; every system runs airgapped unless stated otherwise.

## Architectures

- Hybrid retrieval — vector + keyword + rerank, with attribution to the source span, not a summary
- Context engineering — long-horizon planning, memory, tool-augmented agent loops (ReAct / plan-execute)
- Local & edge — 35B-class models, zero egress, MCP tool interfaces
- Model routing — cheap→expensive cascades bounded by cost & latency
- Guardrails as a pipeline — input / output validation, PII redaction, policy checks
- Eval harnesses — golden sets, deterministic, run as a merge gate

## AI Engineering

- Online evals & regression gates — caught in CI, never in prod
- Observability — LLM traces, token / cost accounting, drift detection
- CUDA / mixed-precision kernels — the gap between a demo and something that ships
- Canary & rolling deploys with semantic caching and graceful degradation
- Prompt + data version control, with lineage
- Agent-driven CI / CD

## Robotics

Legged locomotion · SLAM · sensor fusion · whole-body manipulation · swarm control.

## Languages

`python · rust · typescript · c++ · swift · mojo`

## Tools

`pytorch · tensorflow · docker · cuda · codex/cli · swiftui · node.js`

---

<sub>owner @ gradweight.ch · Switzerland</sub>
