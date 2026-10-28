---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduate student in Software Engineering at the School of Computer
Science and Engineering, Hunan University of Information Technology, Changsha,
China, expecting to graduate in June 2027.

My focus is retrieval for local, on-device LLM applications — what a small
retrieval layer has to be able to show before it is trusted to feed a model that
runs on the user's own machine. Most of my work so far is about evaluation
design rather than about a new scoring function: keeping the candidate sets of
the compared channels identical, freezing the rankings so that every reported
number can be re-derived, and being explicit about who produced the relevance
labels.

## News

- **2026-10** — Our paper *Lightweight Embedded Hybrid Retrieval for Local LLMs:
  Unified Candidate Space and Deployment Trade-offs* was accepted at MLEIL 2026.
  The reproduction bundle is public: [RAG_RRF](https://github.com/xuzeTop1/RAG_RRF).

## Research interests

- Hybrid retrieval: sparse (BM25) and dense channels, rank fusion, and when a
  reported fusion gain is really an index-coverage gain
- Offline evaluation methodology: unified candidate spaces, multi-rater
  relevance labels, paired bootstrap intervals
- Local and privacy-first RAG stacks, and the deployment trade-offs they force
- Cache-aware agent loops for LLM applications

## Selected projects

- [RAG_RRF](https://github.com/xuzeTop1/RAG_RRF) — pseudonymised reproduction
  bundle for the unified-candidate-space evaluation behind my MLEIL 2026 paper.
- [Teacher](https://github.com/xuzeTop1/Teacher) — privacy-first, local-first
  study companion with on-device document retrieval.
- [llm-cache-optimizer](https://github.com/xuzeTop1/llm-cache-optimizer) —
  cache-aware runtime for LLM application loops.
- [research-workbench](https://github.com/xuzeTop1/research-workbench) —
  assistant for paper planning, experiment design and citation auditing; it
  does not ghostwrite.
