---
title: "Scaling Search-Augmented LLM Reasoning via Adaptive Information Control"
collection: publications
category: workshops
permalink: /publication/2026-scaling-search-agents
date: 2026-02-01
image: "scaling_deepcontrol.png"
authors: "S. Xiong, <u>O. Gungordu</u>, B. Johnson, J. C. Kerce, and F. Fekri"
venue: "Workshop on Scaling Post-training for LLMs (SPOT), ICLR&nbsp;2026"
paperurl: "https://arxiv.org/abs/2602.01672v1"
codeurl: "https://github.com/xiongsiheng/DeepControl"
abstract: >-
  Search-augmented reasoning agents interleave multi-step reasoning with external information retrieval, but uncontrolled retrieval often leads to redundant evidence, context saturation, and unstable learning. Existing approaches rely on outcome-based reinforcement learning (RL), which provides limited guidance for regulating information acquisition. We propose DeepControl, a framework for adaptive information control based on a formal notion of information utility, which measures the marginal value of retrieved evidence under a given reasoning state. Building on this utility, we introduce retrieval continuation and granularity control mechanisms that selectively regulate when to continue and stop retrieval, and how much information to expand. An annealed control strategy enables the agent to internalize effective information acquisition behaviors during training. Extensive experiments across seven benchmarks demonstrate that our method consistently outperforms strong baselines. In particular, our approach achieves average performance improvements of 9.4% and 8.6% on Qwen2.5-7B and Qwen2.5-3B, respectively, over strong outcome-based RL baselines, and consistently outperforms both retrieval-free and retrieval-based reasoning methods without explicit information control. These results highlight the importance of adaptive information control for scaling search-augmented reasoning agents to complex, real-world information environments.
---
