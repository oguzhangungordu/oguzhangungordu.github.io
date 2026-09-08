---
title: "PathWise: Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs"
collection: publications
category: conferences
permalink: /publication/2026-pathwise-icml
date: 2026-01-01
image: "pathwise_overview.png"
authors: "<u>O. Gungordu</u>, S. Xiong, and F. Fekri"
venue: "Proceedings of the 43rd International Conference on Machine Learning (ICML&nbsp;2026)"
paperurl: "https://arxiv.org/abs/2601.20539"
codeurl: "https://github.com/oguzhangungordu/PathWise"
abstract: >-
  Large Language Models (LLMs) have enabled automated heuristic design (AHD) for combinatorial optimization problems (COPs), but existing frameworks' reliance on fixed evolutionary rules and static prompt templates often leads to myopic heuristic generation, redundant evaluations, and limited reasoning about how new heuristics should be derived. We propose a novel multi-agent reasoning framework, referred to as Planning through World Model for Automated Heuristic Design via Self-Evolving LLMs (PathWise), which formulates heuristic generation as a sequential decision process over an entailment graph serving as a compact, stateful memory of the search trajectory. This approach allows the system to carry forward past decisions and reuse or avoid derivation information across generations. A policy agent plans evolutionary actions, a world model agent generates heuristic rollouts conditioned on those actions, and critic agents provide routed reflections summarizing lessons from prior steps, shifting LLM-based AHD from trial-and-error evolution toward state-aware planning through reasoning. Experiments across diverse COPs show that PathWise converges faster to better heuristics, generalizes across different LLM backbones, and scales to larger problem sizes.
---
