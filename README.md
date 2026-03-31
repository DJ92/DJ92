![Banner](assets/banner.jpeg)

# Dheeraj Joshi

Systems and machine learning engineer working across retrieval, ranking, recommendation, and GenAI systems.

- Based in Boston, MA
- Focus: search, recommendation, retrieval, GenAI evaluation, agent reliability, and experimentation
- Email: [joshidheeraj1992@gmail.com](mailto:joshidheeraj1992@gmail.com)

## Overview

This profile is a working index of my repositories, design documents, experiments, model cards, and technical writing. The portfolio spans ML systems, GenAI implementations, research reproductions, and writing on retrieval, ranking, recommendation, evaluation, agent reliability, and production trade-offs.

The organizing idea is simple: move from foundations and experiments to production-shaped systems and system design.

## Repository Guide

- [AI Research Portfolio](https://github.com/DJ92/ai-research-portfolio)
  This repo contains research reproductions and evaluation-heavy projects covering transformers, alignment, RAG, tool use, safety, interpretability, and model behavior analysis.
- [GenAI](https://github.com/DJ92/genai)
  This repo contains implementation-focused GenAI systems including RAG, multimodal retrieval, guardrails, workflow platforms, cost optimization, and fine-tuning labs.
- [Applied ML](https://github.com/DJ92/applied-ml)
  This repo contains recommender systems, ranking and retrieval pipelines, serving benchmarks, payment-risk modeling, time series work, and broader applied ML experiments.
- [ML System Design](https://github.com/DJ92/ml-system-design)
  This repo contains written system designs for ranking, retrieval, recommendation, online features, experimentation, rollout, and production ML architecture.
- [Technical Writing](https://dj92.github.io/interview-notes)
  This site contains long-form notes on transformer foundations, evaluation methods, system design, and practical trade-offs in ML and GenAI systems.
- [Hugging Face](https://huggingface.co/Djosh1992)
  This profile contains model cards and public artifacts for experiments such as sequential recommendation and other implementation-focused work.

## Selected Projects and Designs

- [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md)
  This design covers two-stage retrieval plus ranking for large-scale feeds, with feature pipelines, online experimentation, and sub-100ms P99 serving goals.
- [Commerce Recommendation Stack](https://github.com/DJ92/ml-system-design/blob/main/designs/02-commerce-recommendation-stack.md)
  This design connects candidate generation, ranking, online features, ONNX serving, observability, and rollout strategy in one end-to-end commerce ML system.
- [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation)
  This project explores automated metrics, LLM-as-judge workflows, human review, and cost tracking, including public results such as 0.82 judge-human correlation.
- [Real-Time Payment Risk Decisioning](https://github.com/DJ92/applied-ml/tree/main/risk-systems/01-realtime-payment-risk-decisioning)
  This project explores event-time features, streaming-style scoring, review-queue thresholds, and fallback rules for payment-risk decisioning.
- [Sovereign Agent Platform](https://github.com/DJ92/genai/tree/main/sovereign-agent-platform)
  This implementation covers a small-model-first workflow platform with policy gating, ingestion, job orchestration, golden-task evaluation, and a developer CLI.
- [Fine-Tuning + Retrieval Efficiency Lab](https://github.com/DJ92/genai/tree/main/fine-tuning/01-finetuning-retrieval-efficiency)
  This lab compares LoRA-style adaptation and compact retrieval indexes at `768`, `384`, and `256` dimensions under latency, memory, and answer-quality trade-offs.
- [Technical Writing on Evaluation and Transformers](https://dj92.github.io/interview-notes)
  This writing collection focuses on transformer foundations, evaluation methods, and production trade-offs in modern ML and GenAI systems.

## Portfolio Structure

```text
Foundations and reproductions  -> ai-research-portfolio
Research, evaluation, safety   -> ai-research-portfolio + technical writing
Production-shaped GenAI        -> genai
Applied ML implementations     -> applied-ml
System design and architecture -> ml-system-design
External model cards           -> Hugging Face
```

The repos move from core model mechanics to applied systems and production trade-offs.

## Research and Reading Threads

- Transformers and representation learning:
  attention, positional methods, encoder/decoder mechanics, and the building blocks behind transformer-based systems.
- Pretraining, scaling, and efficient tuning:
  BERT-style MLM, GPT-style CLM, scaling-law ideas, LoRA, and QLoRA-style adaptation work.
- Alignment and safety:
  RLHF, DPO, Constitutional AI, chain-of-thought faithfulness, and safety-focused evaluation.
- Retrieval and agents:
  RAG, long-context behavior, tool use, ReAct-style workflows, multimodal retrieval, and grounded generation.
- Recommendation and reinforcement learning:
  neural collaborative filtering, sequential recommenders, multi-behavior user modeling, PPO, and DQN.

The fuller implementation notes for these threads are distributed across the repositories and writing linked above.

## Portfolio at a Glance

- 33 projects across AI research, GenAI systems, applied ML, and system design.
- 6 repository families covering research reproductions, GenAI implementations, applied ML labs, design docs, technical writing, and model cards.
- 22 paper implementations and reading threads spanning transformers, alignment, retrieval, recommendation, and reinforcement learning.
- System constraints covered include 100M+ DAU ranking designs, sub-100ms P99 serving targets, sub-500ms retrieval paths, and low-overhead guardrail patterns.
- Documentation includes README-first project writeups, design documents, and long-form technical notes across the portfolio.
