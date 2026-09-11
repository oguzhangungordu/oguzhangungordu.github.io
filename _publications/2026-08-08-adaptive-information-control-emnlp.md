---
title: "Adaptive Information Control for Search-Augmented LLM Reasoning"
collection: publications
category: conferences
permalink: /publication/2026-adaptive-information-control
date: 2026-08-08
image: "emnlp2026.png"
authors: "S. Xiong, <u>O. Gungordu</u>, J. C. Kerce, and F. Fekri"
venue: "Findings of the Association for Computational Linguistics: EMNLP&nbsp;2026"
paperurl: "https://arxiv.org/abs/2602.01672"
codeurl: "https://github.com/xiongsiheng/DeepControl"
abstract: >-
  Search-augmented reasoning agents interleave multi-step reasoning with external retrieval, but uncontrolled retrieval can introduce redundant evidence, saturate the context, and destabilize reinforcement learning (RL). Existing outcome-based RL methods provide only sparse terminal rewards, offering limited guidance for intermediate information-acquisition decisions. We propose DeepControl, an adaptive information-control framework based on information utility, a state-dependent estimate of the marginal value of retrieved evidence. The framework regulates information acquisition along two axes: extent, i.e., whether retrieval should continue, and resolution, i.e., how much retrieved detail should be exposed. It implements these controls through retrieval-continuation guidance, hierarchical granularity control, and an annealed control-forcing scheme. This enables the policy to internalize effective acquisition behavior during training and operate without external control at test time. Across seven benchmarks, DeepControl consistently outperforms strong RL and retrieval baselines without explicit information control; compared with Search-R1, it improves average performance by +9.4 and +8.6 points on Qwen2.5-7B and Qwen2.5-3B, respectively. Additional analyses show improved search effectiveness, training stability, and evidence utilization.
---
