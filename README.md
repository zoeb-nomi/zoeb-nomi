# Hi, I'm Zoeb Nomi 👋

**AI Product Manager — LLM & agent evaluation, RAG quality.**
I make production AI systems safe to trust in domains where a wrong answer
has professional consequences, not just bad reviews.

Day job: I own LLM output quality for an AI-native tax research platform —
evaluation loops, LLM-as-judge scoring with human validation, competitive
benchmarking across frontier models, and the production retrieval corpus
underneath it all.

## 🔍 CrossSource

**[crosssource](https://github.com/zoeb-nomi/crosssource)** — an MIT-licensed,
reproducible eval harness for citation-level reliability of legal RAG.

- 25 human-authored golden questions over public US case law
- Citation precision/recall with a failure-mode taxonomy, faithfulness, relevance
- LLM judge blind-validated at **100% human agreement** — and the human pass
caught a harness bug the judge scored without noticing
- Headline: citation-discipline prompting lifted precision **0.981 → 0.994**;
recall (0.760) is retrieval-capped, not generation-capped, plus ~95% golden-set citation accuracy across a 270K-record corpus

Currently building **v0.2**: an agent-evaluation module — tool-call
correctness and trajectory scoring for an agentic retrieve → cite →
self-check loop.

## How I think about evals

Quality isn't a vibe; it's a measurement system. Golden sets are
human-authored, judges are validated before they're trusted, and every
score decomposes to a failure mode someone can fix.

📫 [LinkedIn](https://www.linkedin.com/in/zoebnomi) · [zoebnomi.com](https://www.zoebnomi.com)
