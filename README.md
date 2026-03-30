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

## How To Read This Profile

- Recruiter scan in 30 seconds
  Open ML System Design for systems scope, AI Research Portfolio for GenAI depth, and Technical Writing for communication quality.
- Hiring manager scan in 2 minutes
  Look at News Feed Ranking, LLM Evaluation Framework, Agent Safety and Guardrails, and Production RAG for architecture, trade-offs, and metrics.
- Interview prep
  Use each flagship project to practice this sequence: problem, design, trade-offs, metrics, failure modes, and what I would improve in production.

## Interview Paths

### Staff AI/ML Systems

- [News Feed Ranking System Design](https://github.com/DJ92/ml-system-design/blob/main/designs/01-newsfeed-ranking.md)
  Problem: rank large candidate sets for personalized feeds under relevance, freshness, and latency constraints.
  Design: two-stage retrieval plus ranking, feature pipelines, serving, feedback loops, and A/B testing.
  Trade-offs: freshness vs relevance, model complexity vs serving cost, and short-term engagement vs long-term user experience.
  Metrics to discuss: candidate recall, ranking quality, calibration, latency budgets, and experiment outcomes.
  What I learned: staff-level design depends as much on interfaces, observability, and iteration loops as on model choice.
- [LLM Evaluation Framework](https://github.com/DJ92/ai-research-portfolio/tree/main/01-llm-evaluation)
  Problem: evaluate LLM quality across tasks without relying on anecdotes.
  Design: automated metrics, LLM-as-judge, human review workflows, unified clients, and cost tracking.
  Trade-offs: evaluator quality vs evaluation cost, reuse vs task specificity, and judge consistency vs model bias.
  Metrics to discuss: 87% test coverage and 0.82 judge-human correlation.
  What I learned: reliable GenAI systems start with measurement scaffolding, not prompt iteration alone.

### GenAI Evaluation and Reliability

- [Agent Safety & Guardrails](https://github.com/DJ92/ai-research-portfolio/tree/main/05-agent-safety)
  Problem: reduce prompt injection and unsafe behavior in agentic systems.
  Design: layered input checks, approval workflows, behavioral constraints, and red-team testing.
  Trade-offs: safety coverage vs user friction, higher recall vs false positives, and protection vs added latency.
  Metrics to discuss: 94% precision, 88% recall, and attack reduction from defense-in-depth.
  What I learned: safety is a systems problem spanning policy, interfaces, monitoring, and fallback paths.
- [Production RAG System](https://github.com/DJ92/ai-research-portfolio/tree/main/03-rag-system)
  Problem: improve answer quality with retrieval under context-window, latency, and cost constraints.
  Design: chunking experiments, embedding comparisons, hybrid search, reranking, and retrieval metrics.
  Trade-offs: recall vs latency, chunk granularity vs context quality, and semantic search vs keyword robustness.
  Metrics to discuss: 85% MRR@10 and gains from hybrid retrieval.
  What I learned: many RAG failures are retrieval and evaluation failures, not generation failures.

### Search, Retrieval, and Recommendation

- [MB-STR on Hugging Face](https://huggingface.co/Djosh1992/mb-str)
  Problem: model multi-behavior sequential user interactions for recommendation.
  Design: transformer-based sequence modeling over multiple behavior signals instead of treating all events as equivalent.
  Trade-offs: richer behavior modeling vs higher complexity, sequence length vs compute cost, and offline gains vs serving practicality.
  What I learned: recommender quality depends heavily on representing behavior semantics, not just user-item history volume.
- [Applied ML](https://github.com/DJ92/applied-ml)
  Problem: build intuition from collaborative filtering through neural and sequential recommenders.
  Design: matrix factorization, neural collaborative filtering, and GRU-based sequence models.
  Trade-offs: simple baselines vs richer architectures, offline gains vs inference cost, and static preference vs session intent.
  What I learned: strong staff-level judgment starts with knowing which baseline to beat and why.

## Practice Prompts

- How would I debug an online metric regression if offline model metrics stayed flat?
- Which metric mattered most in each project, and why?
- What would I log, alert on, or monitor after launch?
- Where would this system fail first in production?
- What is the simplest version I would ship before scaling complexity?

## Repo README Template

- [Flagship Repo README Template](./FLAGSHIP_REPO_README_TEMPLATE.md)
  A copy-paste template for turning project repos into stronger hiring and interview artifacts.

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
