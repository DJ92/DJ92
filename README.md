![Banner](assets/banner.jpeg)

# Dheeraj Joshi

Senior systems and machine learning engineer building retrieval, ranking, recommendation, and GenAI systems.

I focus on staff-level problems where the challenge is not only model quality, but making the full system measurable, debuggable, safe, and fast enough to ship. My work sits at the boundary of problem framing, offline evaluation, serving and observability, experimentation, and the trade-offs between relevance, latency, cost, and reliability.

- Based in Boston, MA
- Focus: search, recommendation, retrieval, GenAI evaluation, agent reliability, and experimentation
- Email: [joshidheeraj1992@gmail.com](mailto:joshidheeraj1992@gmail.com)

## Best Evidence in 2 Minutes

- [ML System Design](https://github.com/DJ92/ml-system-design)
  Staff AI/ML systems proof: ranking, retrieval, recommendation, latency budgets, experimentation, and production trade-offs.
- [AI Research Portfolio](https://github.com/DJ92/ai-research-portfolio)
  GenAI reliability proof: evaluation, RAG, tool use, safety, interpretability, and transformer foundations across 12 projects.
- [Technical Writing](https://dj92.github.io/interview-notes)
  Communication proof: clear writing on evaluation methods, transformer foundations, and production AI trade-offs.

## Start Here

- [AI Research Portfolio](https://github.com/DJ92/ai-research-portfolio)
  12 projects covering evaluation, RAG, tool use, safety, interpretability, and transformer foundations.
- [ML System Design](https://github.com/DJ92/ml-system-design)
  Production-grade designs for ranking, retrieval, recommendation, and experimentation.
- [GenAI Applications](https://github.com/DJ92/genai)
  Practical systems for RAG, agents, guardrails, cost optimization, and multimodal retrieval.
- [Applied ML](https://github.com/DJ92/applied-ml)
  Broader ML depth across collaborative filtering, neural recommenders, time series, NLP, and classical ML.

## What I Bring

- End-to-end ownership across retrieval, ranking, serving, observability, and experimentation.
- Evaluation-first AI engineering with baselines, failure analysis, human review loops, and explicit cost and latency trade-offs.
- Ability to turn research ideas into deployable systems with strong interfaces and measurable outcomes.
- Clear technical writing that makes decisions, assumptions, and trade-offs easy to review.

## Selected Work

- [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md)
  Two-stage retrieval plus ranking at 100M+ DAU scale with sub-100ms P99 goals, feature pipelines, online experimentation, and multi-objective trade-offs.
- [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation)
  Automated metrics, LLM-as-judge, human evaluation workflows, and cost tracking. Includes 87% test coverage and 0.82 judge-human correlation.
- [Agent Safety & Guardrails](https://github.com/DJ92/ai-research-portfolio/tree/main/05-agent-safety)
  Prompt injection detection, approval workflows, defense-in-depth, and red-team benchmarks. Injection detection reaches 94% precision and 88% recall.
- [Production RAG System](https://github.com/DJ92/ai-research-portfolio/tree/main/03-rag-system)
  Chunking comparisons, retrieval metrics, embedding benchmarks, and hybrid search. Best semantic chunking setup reaches 85% MRR@10.
- [MB-STR on Hugging Face](https://huggingface.co/Djosh1992/mb-str)
  Multi-behavior sequential transformer recommender connecting long-term user behavior modeling with modern recommender system practice.

## What These Projects Demonstrate

- [ML System Design](https://github.com/DJ92/ml-system-design)
  Large-scale ranking, retrieval, recommendation, latency budgets, experimentation, and production trade-offs.
- [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation)
  Evaluation-first GenAI engineering with automated metrics, LLM-as-judge calibration, human review workflows, and cost tracking.
- [Agent Safety & Guardrails](https://github.com/DJ92/ai-research-portfolio/tree/main/05-agent-safety)
  Reliability under adversarial conditions, defense-in-depth, rollout thinking, and measurable safety trade-offs.
- [Production RAG System](https://github.com/DJ92/ai-research-portfolio/tree/main/03-rag-system)
  Retrieval quality, chunking and reranking choices, and offline metrics tied to production constraints.
- [MB-STR on Hugging Face](https://huggingface.co/Djosh1992/mb-str)
  Sequential recommendation depth and multi-behavior user modeling beyond simple user-item histories.

## Portfolio Architecture

My work follows a structured progression from foundations to production systems:

```text
┌─────────────────────────────────────────────────────────────────┐
│                    FOUNDATIONS (12 projects)                   │
│  Transformer Architecture • Pre-training • RLHF/DPO • LoRA    │
│              ai-research-portfolio/09-12                      │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         ▼
┌─────────────────────────────────────────────────────────────────┐
│              RESEARCH & SAFETY (8 projects)                   │
│  Constitutional AI • CoT Faithfulness • Agent Safety          │
│  LLM Evaluation • Interpretability • RAG • Tool Use           │
│              ai-research-portfolio/01-08                      │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         ▼
┌─────────────────────────────────────────────────────────────────┐
│           PRODUCTION GenAI (9 projects + 5 blog posts)        │
│  Production RAG • Agents • Guardrails • Multimodal RAG        │
│  Cost Optimization • Long Context Strategies                  │
│         genai/ + interview-notes/                             │
└────────────────────────┬────────────────────────────────────────┘
                         │
                         ▼
┌─────────────────────────────────────────────────────────────────┐
│          ML SYSTEMS (1 complete + 7 designs, 11 projects)     │
│  News Feed Ranking • RecSys • Time Series • Classical ML • RL │
│         ml-system-design/ + applied-ml/                       │
└─────────────────────────────────────────────────────────────────┘
```

Flow: foundation to research to production to systems demonstrates both depth and breadth.

## Papers Implemented

Research papers implemented across the portfolio:

### Transformers and Attention

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Transformer architecture
- [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864) - RoPE implementation

### Pre-training and Fine-tuning

- [BERT: Pre-training of Deep Bidirectional Transformers](https://arxiv.org/abs/1810.04805) - MLM objective
- [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) - GPT-2 style CLM
- [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) - Chinchilla scaling laws

### Alignment and Safety

- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) - RLHF implementation ideas
- [Direct Preference Optimization](https://arxiv.org/abs/2305.18290) - DPO implementation
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) - critique-revision loop
- [Measuring Faithfulness in Chain-of-Thought Reasoning](https://arxiv.org/abs/2307.13702) - CoT faithfulness analysis

### Parameter-Efficient Fine-tuning

- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) - LoRA implementation
- [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314) - 4-bit quantization

### Retrieval, RAG, and Agents

- [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) - RAG system
- [Lost in the Middle: How Language Models Use Long Contexts](https://arxiv.org/abs/2307.03172) - long-context analysis
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - ReAct agents
- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) - CoT prompting

### Recommendation Systems and RL

- [Neural Collaborative Filtering](https://arxiv.org/abs/1708.05031) - NCF implementation
- [Session-based Recommendations with Recurrent Neural Networks](https://arxiv.org/abs/1511.06939) - GRU4Rec implementation
- [Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347) - PPO implementation
- [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602) - DQN implementation

Total: 22 papers spanning transformers, alignment, efficiency, RAG, agents, recommendation, and RL.

## Portfolio Metrics

Quantitative overview of work across repositories:

- Total projects: 33 across AI research, GenAI systems, applied ML, and system design
- Papers implemented: 22
- Average test coverage across AI research projects: 85%+
- Documentation footprint: 12,000+ lines across READMEs, notes, and system designs
- Scale and latency targets covered: 100M+ DAU ranking systems, sub-100ms P99 serving goals, sub-500ms RAG paths, and low-overhead guardrails
- Cost and quality trade-offs explored: cost optimization, retrieval improvements, evaluation calibration, and production-oriented system simplification
