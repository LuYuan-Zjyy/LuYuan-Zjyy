# Patronum 路 LuYuan-Zjyy

**Time-Series Forecasting 路 LLM Agent Systems**

> Text should make a forecast *explainable*, not just better 鈥?and agents should finish the job.

[**鈫?Visit my site**](https://luyuan-zjyy.github.io) 鈥?animated single-page portfolio (particle field, live counters, timeline).

---

## What I work on

**Time-series forecasting.** Why text helps a forecaster 鈥?and where it hurts. Multimodal modeling over numeric
series plus repository / document text, with ablations that show which input actually moved the number.

**LLM agent systems.** Orchestrator + specialist workers, evidence-grounded reranking instead of free-form
generation, RAG and tool-calling, shipped as containerized services.

*Side track:* cold-start cross-domain recommendation with multi-prototype uncertainty transfer.

---

## Featured projects

### 馃攳 [factguardian](https://github.com/LuYuan-Zjyy/factguardian)

[![stars](https://img.shields.io/github/stars/LuYuan-Zjyy/factguardian?style=flat-square&color=f59e0b)](https://github.com/LuYuan-Zjyy/factguardian/stargazers)
[![issues](https://img.shields.io/github/issues/LuYuan-Zjyy/factguardian?style=flat-square)](https://github.com/LuYuan-Zjyy/factguardian/issues)
[![license](https://img.shields.io/github/license/LuYuan-Zjyy/factguardian?style=flat-square)](https://github.com/LuYuan-Zjyy/factguardian/blob/main/LICENSE)

Audit long documents for factual consistency: extract facts, catch numeric / logical / temporal contradictions,
verify claims against the web, and check figures against text. FastAPI + React + Redis, Docker-ready.

> `parse 鈫?extract 鈫?detect 鈫?verify` 路 MinHash pre-filter cuts pairwise comparisons 50鈥?00脳 路 one command to run.

### 馃Л [Traveling-v2](https://github.com/LuYuan-Zjyy/Traveling-v2)

[![stars](https://img.shields.io/github/stars/LuYuan-Zjyy/Traveling-v2?style=flat-square&color=22c55e)](https://github.com/LuYuan-Zjyy/Traveling-v2/stargazers)
[![issues](https://img.shields.io/github/issues/LuYuan-Zjyy/Traveling-v2?style=flat-square)](https://github.com/LuYuan-Zjyy/Traveling-v2/issues)

A multi-agent travel planner: one sentence in, a mapped and budget-aware itinerary out. Orchestrator + specialist
agents (culture, budget, route, guide, quality-eval) over AMap Web Services, rendered on Leaflet, with export to
the TravelPlanner / TripTailor benchmarks.

> Flask + Leaflet UI 路 agent state / memory / context kept per stage 路 benchmark export so plans are scored, not eyeballed.

### 馃 [psycon-assist](https://github.com/LuYuan-Zjyy/psycon-assist)

[![stars](https://img.shields.io/github/stars/LuYuan-Zjyy/psycon-assist?style=flat-square&color=a855f7)](https://github.com/LuYuan-Zjyy/psycon-assist/stargazers)
[![issues](https://img.shields.io/github/issues/LuYuan-Zjyy/psycon-assist?style=flat-square)](https://github.com/LuYuan-Zjyy/psycon-assist/issues)

An auditable session-analysis assistant for psychological counseling. Every observation is tied to evidence,
severity comes from a rule table rather than a model, the LLM is reachable only at two named nodes, and clinician
feedback is captured with six fixed reason codes.

> 7-stage pipeline (ingest 鈫?signals 鈫?chunks 鈫?events 鈫?agent 鈫?feedback 鈫?profile) 路 23 hard rules 路 refuses cross-session claims below 0.7 comparability.

---

## Selected work

| Project | What it is | Result |
| :-- | :-- | :-- |
| [**GitPulse / OpenVista**](https://github.com/LuYuan-Zjyy/GitPulse) | 16 OpenDigger metrics 脳 repo text, 32-month forecast + LLM explainer | MSE 0.0886 路 R虏 0.70 路 DA 67.28% |
| [**factguardian**](https://github.com/LuYuan-Zjyy/factguardian) | cloud-native fact-consistency agent for long docs | extract 鈫?cross-check 鈫?trace |
| [**Traveling-v2**](https://github.com/LuYuan-Zjyy/Traveling-v2) | multi-agent itinerary planner over AMap + map UI | 7 agents 路 benchmark export |
| [**psycon-assist**](https://github.com/LuYuan-Zjyy/psycon-assist) | auditable counseling session analysis | 23 rules 路 evidence-linked events |
| [**InteractiveFusion-Sentiment**](https://github.com/LuYuan-Zjyy/InteractiveFusion-Sentiment) | image-text sentiment: dynamic-weighted IIF + sentiment-prototype SIE | Acc 84.7% 路 F1 84.0% 路 +3.5pt |

## Research

| Work | Role | Status | Key result |
| :-- | :-- | :-- | :-- |
| **CrossBridge** 路 cross-domain rec | co-first | submitted 路 ICDM 2026 | negative transfer 鈫?1/3 |
| **Time-series & text** 路 attribution of multimodal gains | first | in progress | which text input actually moves the forecast |
| **InteractiveFusion-Sentiment** | solo | complete | 84.7% / 84.0% F1 |
| **Deepfake audio** 路 dual-branch Conformer | third | under review 路 ASC | lower EER on CFAD |

## Stack

`Python` `C++` `SQL` `TypeScript` 路 `PyTorch` `Transformers` `Mamba/SSM` `Conformer` 路 `LangChain` `LangGraph` `RAG` `LoRA` 路 `FastAPI` `React` `Docker` `Redis`

## Open source

19 public repositories 鈥?dataset pipelines, models, services and evaluation harnesses, all readable end to end.
The three projects above have `good first issue` labels and issue templates; contributions are welcome.

鈫?[browse all repositories](https://github.com/LuYuan-Zjyy?tab=repositories)

---

馃摣 [github.com/LuYuan-Zjyy](https://github.com/LuYuan-Zjyy) 路 2079685390@qq.com
