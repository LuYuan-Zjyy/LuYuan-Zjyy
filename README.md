# Patronum · LuYuan-Zjyy

**Time-Series Forecasting · LLM Agent Systems**

> Text should make a forecast *explainable*, not just better — and agents should finish the job.

[**↗ Visit my site**](https://luyuan-zjyy.github.io) — animated single-page portfolio (particle field, live counters, timeline).

---

## What I work on

**Time-series forecasting.** Why text helps a forecaster — and where it hurts. Multimodal modeling over numeric
series plus repository / document text, with ablations that show which input actually moved the number.

**LLM agent systems.** Orchestrator + specialist workers, evidence-grounded reranking instead of free-form
generation, RAG and tool-calling, shipped as containerized services.

*Side track:* cold-start cross-domain recommendation with multi-prototype uncertainty transfer.

---

## Featured projects

### factguardian

[![stars](https://img.shields.io/github/stars/LuYuan-Zjyy/factguardian?style=flat-square&color=f59e0b)](https://github.com/LuYuan-Zjyy/factguardian/stargazers)
[![issues](https://img.shields.io/github/issues/LuYuan-Zjyy/factguardian?style=flat-square)](https://github.com/LuYuan-Zjyy/factguardian/issues)
[![license](https://img.shields.io/github/license/LuYuan-Zjyy/factguardian?style=flat-square)](https://github.com/LuYuan-Zjyy/factguardian/blob/main/LICENSE)

Audit long documents for factual consistency: extract facts, catch numeric / logical / temporal contradictions,
verify claims against the web, and check figures against text. FastAPI + React + Redis, Docker-ready.

> `parse → extract → detect → verify` · MinHash pre-filter cuts pairwise comparisons 50–600× · one command to run.

### Traveling-v2

[![stars](https://img.shields.io/github/stars/LuYuan-Zjyy/Traveling-v2?style=flat-square&color=22c55e)](https://github.com/LuYuan-Zjyy/Traveling-v2/stargazers)
[![issues](https://img.shields.io/github/issues/LuYuan-Zjyy/Traveling-v2?style=flat-square)](https://github.com/LuYuan-Zjyy/Traveling-v2/issues)

A multi-agent travel planner: one sentence in, a mapped and budget-aware itinerary out. Orchestrator + specialist
agents (culture, budget, route, guide, quality-eval) over AMap Web Services, rendered on Leaflet, with export to
the TravelPlanner / TripTailor benchmarks.

> Flask + Leaflet UI · agent state / memory / context kept per stage · benchmark export so plans are scored, not eyeballed.

### psycon-assist

[![stars](https://img.shields.io/github/stars/LuYuan-Zjyy/psycon-assist?style=flat-square&color=a855f7)](https://github.com/LuYuan-Zjyy/psycon-assist/stargazers)
[![issues](https://img.shields.io/github/issues/LuYuan-Zjyy/psycon-assist?style=flat-square)](https://github.com/LuYuan-Zjyy/psycon-assist/issues)

An auditable session-analysis assistant for psychological counseling. Every observation is tied to evidence,
severity comes from a rule table rather than a model, the LLM is reachable only at two named nodes, and clinician
feedback is captured with six fixed reason codes.

> 7-stage pipeline (ingest → signals → chunks → events → agent → feedback → profile) · 23 hard rules · refuses cross-session claims below 0.7 comparability.

---

## Selected work

| Project | What it is | Result |
| :-- | :-- | :-- |
| [**GitPulse / OpenVista**](https://github.com/LuYuan-Zjyy/GitPulse) | 16 OpenDigger metrics × repo text, 32-month forecast + LLM explainer | MSE 0.0886 · R² 0.70 · DA 67.28% |
| [**factguardian**](https://github.com/LuYuan-Zjyy/factguardian) | cloud-native fact-consistency agent for long docs | extract → cross-check → trace |
| [**Traveling-v2**](https://github.com/LuYuan-Zjyy/Traveling-v2) | multi-agent itinerary planner over AMap + map UI | 7 agents · benchmark export |
| [**psycon-assist**](https://github.com/LuYuan-Zjyy/psycon-assist) | auditable counseling session analysis | 23 rules · evidence-linked events |
| [**InteractiveFusion-Sentiment**](https://github.com/LuYuan-Zjyy/InteractiveFusion-Sentiment) | image-text sentiment: dynamic-weighted IIF + sentiment-prototype SIE | Acc 84.7% · F1 84.0% · +3.5pt |

## Research

| Work | Role | Status | Key result |
| :-- | :-- | :-- | :-- |
| **CrossBridge** · cross-domain rec | co-first | submitted · ICDM 2026 | negative transfer → 1/3 |
| **Time-series & text** · attribution of multimodal gains | first | in progress | which text input actually moves the forecast |
| **InteractiveFusion-Sentiment** | solo | complete | 84.7% / 84.0% F1 |
| **Deepfake audio** · dual-branch Conformer | third | under review · ASC | lower EER on CFAD |

## Stack

`Python` `C++` `SQL` `TypeScript` · `PyTorch` `Transformers` `Mamba/SSM` `Conformer` · `LangChain` `LangGraph` `RAG` `LoRA` · `FastAPI` `React` `Docker` `Redis`

## Open source

19 public repositories — dataset pipelines, models, services and evaluation harnesses, all readable end to end.
The three projects above have `good first issue` labels and issue templates; contributions are welcome.

→ [browse all repositories](https://github.com/LuYuan-Zjyy?tab=repositories)

---

📫 [github.com/LuYuan-Zjyy](https://github.com/LuYuan-Zjyy) · 2079685390@qq.com
