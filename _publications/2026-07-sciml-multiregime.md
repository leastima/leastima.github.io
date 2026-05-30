---
title: "Unveiling Multi-regime Patterns in SciML: Distinct Failure Modes and Regime-specific Optimization"
collection: publications
category: conferences
permalink: /publication/2026-sciml-multiregime
excerpt: "We study multi-regime behavior in scientific machine learning (SciML) models through a regime-aware diagnostic framework that jointly analyzes performance, training dynamics, and loss-landscape geometry. We identify a consistent three-regime structure across PINNs, Neural Operators, and Neural ODEs, show that optimization effectiveness is regime-specific, and uncover fine-grained failure modes (e.g., deceptive sharpness and flatness) that challenge conventional loss-landscape interpretations."
date: 2026-07-01
venue: "International Conference on Machine Learning (ICML)"
paperurl: "https://arxiv.org/pdf/2605.29153"
citation: "Yuxin Wang, Yuanzhe Hu, Xiaokun Zhong, Xiaopeng Wang, Haiquan Lu, Tianyu Pang, Michael W. Mahoney, Yujun Yan, Pu Ren, Yaoqing Yang. (2026). &quot;Unveiling Multi-regime Patterns in SciML: Distinct Failure Modes and Regime-specific Optimization.&quot; <i>ICML 2026</i>."
---

Neural networks trained under different hyperparameter settings can fall into distinct training "regimes," with consistent behavior within regimes and qualitative differences across regimes. In this paper, we study such multi-regime behavior in scientific machine learning (SciML) models through a **regime-aware diagnostic framework** that jointly analyzes performance, training dynamics, and loss-landscape geometry.

**Key findings:**
1. A consistent **three-regime structure** (Well-Trained, Under-Trained, Over-Trained) emerges across many standard SciML models, different constraint enforcements, and various optimizer designs.
2. **Optimization effectiveness is regime-specific**: no single method performs well across all regimes.
3. SciML models can exhibit **fine-grained failure modes** — including *deceptive sharpness* and *deceptive flatness* — that challenge conventional interpretations of standard loss-landscape metrics.

We validate these findings across widely-used SciML models, including physics-informed neural networks (PINNs), neural operators (FNO, PINO), and neural ordinary differential equations (NODE, PINODE), on benchmarks spanning representative ODEs and PDEs.

**Links:** [arXiv](https://arxiv.org/abs/2605.29153) | [Code](https://github.com/leastima/sciml_multi_regime)
