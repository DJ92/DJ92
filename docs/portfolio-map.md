# Portfolio Map

This document is the cross-repo reading guide for the public portfolio. The goal is to make the relationship between code, design, evaluation, and writing obvious without collapsing everything into one oversized repository.

## Recommended Reading Paths

### 10-minute overview

1. Start at the [profile README](../README.md).
2. Read [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform) for agent workflow depth.
3. Read [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md) for architecture judgment.
4. Read [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation) for eval discipline.

### 25-minute agent systems path

1. [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform)
2. [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation)
3. [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency)
4. [Technical Writing](https://dj92.github.io/interview-notes)

### 25-minute retrieval, ranking, and personalization path

1. [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md)
2. [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md)
3. [Real-Time Payment Risk Decisioning](https://github.com/DJ92/applied-ml/tree/main/risk-systems/01-realtime-payment-risk-decisioning)
4. [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency)

## Cross-Repo Artifact Matrix

| Theme | Code artifact | Design / architecture | Eval / benchmark | Writing / notes | Focus |
| --- | --- | --- | --- | --- | --- |
| Agent workflows and regression discipline | [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform) | [ML System Design](https://github.com/DJ92/ml-system-design) | [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation) | [Technical Writing](https://dj92.github.io/interview-notes) | Async jobs, policy gating, golden-task evaluation, and production trade-off framing. |
| Retrieval, ranking, and recommendation | [Applied ML](https://github.com/DJ92/applied-ml) | [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md) | [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency) | [Technical Writing](https://dj92.github.io/interview-notes) | Candidate generation, ranking, serving, and experimentation under practical latency constraints. |
| Reliability and rollout thinking | [Real-Time Payment Risk Decisioning](https://github.com/DJ92/applied-ml/tree/main/risk-systems/01-realtime-payment-risk-decisioning) | [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md) | Thresholds, review queues, and fallback rules in code | [Technical Writing](https://dj92.github.io/interview-notes) | Failure modes, controls, and staged rollout decisions. |
| Efficiency and local-inference pragmatism | [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency) | [Hugging Face](https://huggingface.co/Djosh1992) | Dimension comparisons at `768`, `384`, and `256` | [Technical Writing](https://dj92.github.io/interview-notes) | Cost-aware deployment, compact retrieval, and small-model-first engineering. |

## Why The Portfolio Is Structured This Way

- Code lives in the repo that best fits the implementation domain.
- Design docs stay separate so architecture thinking is readable without digging through source trees.
- Evaluation and benchmark artifacts are highlighted independently so claims are easier to verify.
- The profile repo acts as the public index that connects these artifacts into one coherent story.
