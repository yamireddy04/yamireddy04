<div align="center">
  
# Yamini G

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=zYTRPeIAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0004-9662-0219)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yamini-nlp/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://yamini-portfolio-ten.vercel.app)

</div>

---

CS graduate. I study how AI systems fail when sentiment, confidence,
and surface fluency masks the signal that actually matters — user
intent, factual grounding, and decision-relevant uncertainty.

---

## Research

Three preprints on sentiment analysis, intent modeling, and
human-AI communication. All self-initiated during undergraduate
study.

| Paper | Venue | Links | Implementation |
|-------|-------|-------|----------------|
| **Sentiment-Aware Reflective Writing Systems** — formalizes the gap between sentiment polarity S(x) and intent interpretation I(x,C,G,H); proposes utility-theoretic response selection with configurable asymmetric cost weights | TechRxiv · IEEE | [DOI](https://doi.org/10.36227/techrxiv.177274130.07417144/v1) | [MindNook](https://github.com/yamini-nlp/MindNook-HCJ) (pinned) |
| **Beyond Surface Affect** — proves formally that sentiment detection does not imply intent interpretation; identifies four canonical failure modes, implemented as a four-layer intent-modeling pipeline | TechRxiv · IEEE | [DOI](https://doi.org/10.36227/techrxiv.177274129.99249714/v1) | [InterviewIQ](https://github.com/yamini-nlp/InterviewIQ) (pinned) |
| **YouTube Transcript vs Comment Sentiment** — dual-model pipeline documenting divergence patterns across five content domains; failure modes in public discourse analysis | SSRN | [DOI](https://doi.org/10.2139/ssrn.6344859) | [Repo](https://github.com/yamini-nlp/youtube-sentiment-analysis-ai) |

---

## Projects

| Project | What it addresses |
|---------|-------------------|
| [MindNook](https://github.com/yamini-nlp/MindNook-HCJ) | Prototype of a published TechRxiv framework: five-layer NLP pipeline (sentiment, pragmatics, temporal trend, goal alignment, utility-based action selection) with a two-stage safety layer (negation-aware crisis screening + LLM output moderation) and user-adjustable intervention thresholds. Supabase/Deno + Groq Llama 3.3 70B, Postgres RLS, 35-test Vitest suite. |
| [InterviewIQ](https://github.com/yamini-nlp/InterviewIQ) | Reference implementation of a second published framework: a four-layer Multi-Layer Intent Model (affect, pragmatics, goal-state tracking, intent fusion) for interview-answer analysis — belief tracking over candidate goals, live facial-affect signal, refresh-token rotation with reuse detection, 66-test suite (FastAPI + Next.js). |
| [LLM Reliability Lab](https://github.com/yamini-nlp/llm-reliability-lab) | Hallucination benchmarking across 3 live LLMs via Groq (Llama 3.1/3.3, GPT-OSS 120B) — dual heuristic + LLM-as-judge scoring, Wilson confidence intervals. CoT reached 87.5% vs. 85.0% zero-shot accuracy (n=40, overlapping CIs). |
| [Prism](https://github.com/yamini-nlp/prism) | Hybrid dense+BM25 RAG pipeline with cross-encoder reranking and claim-level hallucination detection; JWT-authenticated multi-user backend (Postgres/pgvector, Redis) with CI/CD and a Wilson-CI evaluation harness (Recall@5, MRR, groundedness rate). |
| [CrisisRadar](https://github.com/yamini-nlp/CrisisRadar) | Real-time geospatial disaster intelligence platform — hexagonal-architecture FastAPI backend across 12 services (Airflow, Celery/RabbitMQ, Prometheus/Grafana), a trained IsolationForest anomaly detector exercised end-to-end on live USGS seismic data, and an explicit rule-based fallback path for models not yet trained. 163-test suite (FastAPI + Next.js). |
| [PrepSphere](https://github.com/yamini-nlp/PrepSphere) | AI placement-prep platform built as a controlled comparison of two LLM-reliability strategies — a direct synchronous proxy vs. a Zod-validated, retry-backed BullMQ job queue — with a 120-run evaluation harness that surfaced a real error-swallowing bug hiding rate limits and schema mismatches behind one fallback path. |
| [PrognosAI](https://github.com/yamini-nlp/Prognos-AI) | Clinical NLP: 30-day readmission, LOS, and specialty prediction from discharge notes across three architectures (TF-IDF, vitals-hybrid, LLM), with SHAP/phrase-level explainability — reported honestly at near-chance accuracy on two of three tasks, with the third task's apparent perfect score traced to likely vocabulary leakage in the synthetic dataset. |
| [Fake News Detector](https://github.com/yamini-nlp/fakenews_detector) | Multi-signal fusion: XLM-RoBERTa + Google Fact Check API + propagation-graph features on the LIAR dataset, combined via a confidence-dampened weighted ensemble (FastAPI + React). |

---

## Technical Areas

`NLP` `Transformer Fine-tuning` `LLM Evaluation` `Hallucination Detection`
`Retrieval-Augmented Generation` `Clinical AI` `Sentiment Analysis`
`Intent Modeling` `Computer Vision` `Time-Series Anomaly Detection`
`Geospatial Systems` `Workflow Orchestration` `Monitoring`
`PyTorch` `scikit-learn` `FAISS` `FastAPI` `Next.js`

---

<div align="center">

*CS graduate · 3 preprints · 8 projects · NLP, LLM reliability & applied AI systems*

</div>
