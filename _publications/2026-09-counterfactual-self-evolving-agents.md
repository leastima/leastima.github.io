---
title: "Counterfactual Self-Evolving Agents for Evidence-Grounded Reasoning"
collection: publications
category: manuscripts
permalink: /publication/2026-counterfactual-self-evolving-agents
excerpt: "We introduce counterfactual self-evolution, in which a trainable proposer constructs targeted evidence edits and causal explanations, while accepted counterfactuals accumulate in memory to improve a frozen solver across clinical, fact-verification, and business reasoning tasks."
date: 2026-09-26
venue: "arXiv preprint"
paperurl: "https://arxiv.org/pdf/2609.32870"
citation: "Xing Han, Yuxin Wang, Chen Chen, Wei Dai, Gautham Krishna Gudur, Shijun Li, Hsing-Huan Chung, Gregory D. Hager, Joydeep Ghosh, Paul Pu Liang, Suchi Saria. (2026). &quot;Counterfactual Self-Evolving Agents for Evidence-Grounded Reasoning.&quot; <i>arXiv preprint arXiv:2609.32870</i>."
---

Self-play proposer-solver methods are difficult to apply to evidence-identifiable tasks, where answers depend on case-specific evidence and domain knowledge. We introduce **counterfactual self-evolution**, a framework in which a trainable proposer constructs targeted evidence edits and explains their potential causal effects on a decision.

The proposer is instruction-tuned on an expert-verified counterfactual dataset and optimized with feedback from a solver and verifier. Accepted counterfactuals accumulate in memory and provide evolving in-context evidence to a frozen solver, allowing the system to improve without updating the solver's weights.

We evaluate the framework across clinical reasoning, fact verification, and business reasoning, including transfer to harder cases and multiple frontier models.

**Links:** [arXiv](https://arxiv.org/abs/2609.32870)
