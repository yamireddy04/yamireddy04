<div align="center">
  
# Yamini G

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=zYTRPeIAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0004-9662-0219)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yamini-gabu/)
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
| **Sentiment-Aware Reflective Writing Systems** — formalizes the gap between sentiment polarity S(x) and intent interpretation I(x,C,G,H); proposes utility-theoretic response selection with configurable asymmetric cost weights | TechRxiv · IEEE | [DOI](https://doi.org/10.36227/techrxiv.177274130.07417144/v1) | MindNook (pinned) |
| **Beyond Surface Affect** — proves formally that sentiment detection does not imply intent interpretation; identifies four canonical failure modes with deployed prototype observations | TechRxiv · IEEE | [DOI](https://doi.org/10.36227/techrxiv.177274129.99249714/v1) | Under active development |
| **YouTube Transcript vs Comment Sentiment** — dual-model pipeline documenting divergence patterns across five content domains; failure modes in public discourse analysis | SSRN | [DOI](https://doi.org/10.2139/ssrn.6344859) | [Repo](https://github.com/yamireddy04/youtube-sentiment-analysis-ai) |

---

## Projects

| Project | What it addresses |
|---------|-------------------|
| [LLM Reliability Lab](https://github.com/yamireddy04/llm-reliability-lab) | Hallucination benchmarking across 3 live LLMs via Groq (Llama 3.1/3.3, GPT-OSS 120B) — dual heuristic + LLM-as-judge scoring, Wilson confidence intervals. CoT reached 87.5% vs. 85.0% zero-shot accuracy (n=40, overlapping CIs). |
| [MindNook](https://github.com/yamireddy04/MindNook-HCJ) | Prototype of published TechRxiv framework — five-layer NLP architecture with utility-theoretic action selection and ethical filter |
| [Fake News Detector](https://github.com/yamireddy04/fakenews_detector) | Multi-signal fusion: XLM-RoBERTa + Google Fact Check API + propagation graph features on LIAR dataset |
| [PrognosAI](https://github.com/yamireddy04/Prognos-AI) | Clinical NLP: 30-day readmission, LOS, and specialty prediction from discharge notes — three pipelines (TF-IDF, vitals-hybrid, LLM), SHAP/phrase-level explainability, CI + Docker |
| [Prism](https://github.com/yamireddy04/prism) | RAG pipeline with claim-level hallucination detection — unsupported claims flagged before reaching the user |
| [PrepSphere](https://github.com/yamireddy04/PrepSphere) | AI placement-prep platform with dual LLM reliability paths — live Groq proxy + BullMQ async queue with Zod schema validation. Node.js · MongoDB · Vanilla JS. |

---

## Technical Areas

`NLP` `Transformer Fine-tuning` `LLM Evaluation` `Hallucination Detection`
`Retrieval-Augmented Generation` `Clinical AI` `Sentiment Analysis`
`Intent Modeling` `PyTorch` `scikit-learn` `FAISS` `FastAPI` `Next.js`

---

<div align="center">

*CS graduate · 3 preprints · 6 deployed systems · NLP & LLM reliability*

</div>
