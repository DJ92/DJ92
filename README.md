![Banner](assets/banner.jpeg)

# Dheeraj Joshi

Projects, design notes, and technical writing across retrieval, ranking, recommendation, and GenAI systems.

- Based in Boston, MA
- Topics: agent workflows, retrieval/ranking, GenAI evaluation, reliability, and experimentation
- Email: [joshidheeraj1992@gmail.com](mailto:joshidheeraj1992@gmail.com)

## Overview

This profile is a working index of my repositories, design documents, experiments, model cards, and technical writing. The collection spans ML systems, GenAI implementations, research reproductions, and writing on retrieval, ranking, recommendation, evaluation, agent reliability, and production trade-offs.

The organizing idea is simple: show the full loop from system design to implementation to evaluation to production trade-offs.

## Reading Paths

| If you want to explore | Start with | Then read |
| --- | --- | --- |
| Agent workflows and eval discipline | [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform) | [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation), [portfolio map](docs/portfolio-map.md) |
| Retrieval, ranking, and personalization | [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md) | [Real-Time Payment Risk Decisioning](https://github.com/DJ92/applied-ml/tree/main/risk-systems/01-realtime-payment-risk-decisioning), [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md) |
| System design and technical writing | [ML System Design](https://github.com/DJ92/ml-system-design) | [Technical Writing](https://dj92.github.io/interview-notes), [portfolio map](docs/portfolio-map.md) |

## Recent Additions

- `2026-03-30`: [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform) adds small-model-first orchestration, policy gating, background jobs, and golden-task evaluation for agent workflows.
- `2026-03-30`: [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency) compares retrieval index dimensions and adaptation choices under latency, memory, and answer-quality trade-offs.
- `2026-03-30`: [Real-Time Payment Risk Decisioning](https://github.com/DJ92/applied-ml/tree/main/risk-systems/01-realtime-payment-risk-decisioning) packages streaming-style features, scoring thresholds, and fallback rules into a production-shaped decisioning workflow.

## Themes Across The Work

| Theme | Code artifact | Design / architecture | Eval / evidence | What it covers |
| --- | --- | --- | --- | --- |
| Agent workflows and reliability | [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform) | [ML System Design](https://github.com/DJ92/ml-system-design) | [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation) | Shows async orchestration, policy gates, task routing, and regression discipline instead of a thin chatbot wrapper. |
| Retrieval, ranking, and recommendation | [Applied ML](https://github.com/DJ92/applied-ml) | [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md) | [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency) | Shows candidate generation, ranking, latency budgets, experimentation, and trade-off thinking across retrieval-heavy systems. |
| Efficiency and deployment pragmatism | [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency) | [Hugging Face](https://huggingface.co/Djosh1992) | Benchmarks at `768`, `384`, and `256` dimensions | Shows cost-aware deployment taste, compact retrieval choices, and small-model-first thinking. |
| System design and rollout thinking | [ML System Design](https://github.com/DJ92/ml-system-design) | [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md) | [Technical Writing](https://dj92.github.io/interview-notes) | Covers architecture judgment, rollout constraints, observability expectations, and long-form design notes. |

## Repository Guide

| Repo | Role in the collection |
| --- | --- |
| [AI Research Portfolio](https://github.com/DJ92/ai-research-portfolio) | Research reproductions and evaluation-heavy projects covering alignment, tool use, interpretability, and model behavior analysis. |
| [GenAI](https://github.com/DJ92/genai) | Implementation-focused GenAI systems around agents, multimodal retrieval, guardrails, cost optimization, and fine-tuning labs. |
| [Applied ML](https://github.com/DJ92/applied-ml) | Ranking, retrieval, recommendation, payment-risk modeling, and broader applied ML implementations. |
| [ML System Design](https://github.com/DJ92/ml-system-design) | Written system designs for ranking, retrieval, recommendation, experimentation, rollout, and production ML architecture. |
| [Technical Writing](https://dj92.github.io/interview-notes) | Long-form notes on transformer foundations, evaluation methods, and practical ML and GenAI trade-offs. |
| [Hugging Face](https://huggingface.co/Djosh1992) | Model cards and public artifacts for implementation-focused experiments. |

## Selected Projects and Designs

- [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform)
  This implementation covers a small-model-first workflow platform with policy gating, ingestion, job orchestration, golden-task evaluation, and a developer CLI.
- [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation)
  This project explores automated metrics, LLM-as-judge workflows, human review, and cost tracking, including public results such as 0.82 judge-human correlation.
- [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency)
  This lab compares LoRA-style adaptation and compact retrieval indexes at `768`, `384`, and `256` dimensions under latency, memory, and answer-quality trade-offs.
- [Real-Time Payment Risk Decisioning](https://github.com/DJ92/applied-ml/tree/main/risk-systems/01-realtime-payment-risk-decisioning)
  This project explores event-time features, streaming-style scoring, review-queue thresholds, and fallback rules for payment-risk decisioning.
- [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md)
  This design connects candidate generation, ranking, online features, ONNX serving, observability, and rollout strategy in one end-to-end commerce ML system.
- [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md)
  This design covers two-stage retrieval plus ranking for large-scale feeds, with feature pipelines, online experimentation, and sub-100ms P99 serving goals.
- [Technical Writing on Evaluation and Transformers](https://dj92.github.io/interview-notes)
  This writing collection focuses on transformer foundations, evaluation methods, and production trade-offs in modern ML and GenAI systems.

## How The Repos Fit Together

```text
Profile entrypoint             -> DJ92
Production-shaped GenAI        -> genai
Evaluation and reproductions   -> ai-research-portfolio
Ranking and retrieval systems  -> applied-ml
System design and architecture -> ml-system-design
Writing and model cards        -> technical writing + Hugging Face
```

The profile README is the entrypoint. The linked repos hold the code, design docs, evals, and writing in separate but connected artifacts. For a cross-repo reading guide, see [docs/portfolio-map.md](docs/portfolio-map.md).

## What Repeats Across The Work

- Evaluation loops before claims.
- Retrieval and ranking before generation-only abstractions.
- Policy gates, fallbacks, and rollout thinking for agent and ML systems.
- Latency, memory, and cost trade-offs made explicit in docs and examples.
- Separate code, design, and writing artifacts so each repo stays navigable.

## At A Glance

- 33 projects across AI research, GenAI systems, applied ML, and system design.
- 6 repository families covering research reproductions, GenAI implementations, applied ML labs, design docs, technical writing, and model cards.
- 22 paper implementations and reading threads spanning transformers, alignment, retrieval, recommendation, and reinforcement learning.
- System constraints covered include 100M+ DAU ranking designs, sub-100ms P99 serving targets, sub-500ms retrieval paths, golden-task agent evals, and low-overhead guardrail patterns.
- Documentation includes README-first project writeups, design documents, long-form technical notes, and a cross-repo [portfolio map](docs/portfolio-map.md).
