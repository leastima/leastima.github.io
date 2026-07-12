---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF Resume](/files/resume4res.pdf){: .btn .btn--info}

---

Education
======
* **M.S.E. in Data Science**, Johns Hopkins University, Jan 2026 – Present  
  Department of Applied Mathematics and Statistics, Baltimore, MD · GPA: 3.58 / 4.0

* **B.E. in Data Science and Big Data Technology**, Tongji University, Sep 2019 – Jun 2023  
  College of Electronics and Information Engineering, Shanghai, China · GPA: 3.55 / 4.0  
  Key Courses: C/C++/Python Programming, Operating System, Data Mining, Data Structure and Algorithm Design, Big Data Management Systems, Cloud Computing, Machine Learning, Artificial Intelligence

Research Experience
======
* **Self-Evolving Medical Agent via Counterfactual Reasoning**, Mar 2026 – Present  
  Advisor: Dr. Xing Han, Johns Hopkins University
  * Designed and implemented an end-to-end self-evolving pipeline for ICU clinical prediction.
  * Curated a 300-example counterfactual dataset from MIMIC-IV; fine-tuned Qwen2.5-7B to improve counterfactual quality.
  * Confidence-gated memory injection improved AUROC from 0.736 → 0.804, accuracy 0.727 → 0.840, and F1 0.349 → 0.478 on in-hospital mortality prediction.
  * Extending the framework to multitask ICU prediction (mortality, length-of-stay, phenotyping).

* **Loss Landscape Analysis of Scientific Machine Learning Models**, Mar 2025 – May 2026  
  Advisor: [Prof. Yaoqing Yang](https://web.cs.dartmouth.edu/people/yaoqing-yang) and [Pu Ren](https://paulpuren.github.io/), Dartmouth College
  * Developed measurement of mode connectivity in PINNs; characterized optimization regimes based on Hessian, CKA, and mode connectivity.
  * Conducted systematic comparisons of soft and hard constraint methods (Fourier parameterization, penalty method, Augmented Lagrangian Method, Trust-Region SQP) to analyze performance across different regimes.
  * Identified and explained several pathological phenomena in SciML that differ from those observed in computer vision, from a loss landscape perspective.
  * Paper accepted at **ICML 2026**.

* **Low-light Image Enhancement Based on Attention Mechanism**, Mar 2023 – Jun 2023  
  * Reproduced Illumination Adaptive Transformer and Multi-Axis MLP; conducted experiments on LOL and SICE datasets.
  * Optimized deep convolution enhancement module in the local branch by incorporating SWIN attention.
  * Attempted to incorporate black level correction transformation matrices from ISP into the global branch.
  * Project received 50+ forks on Kaggle; achieved PSNR of 0.65 and SSIM of 20.45.

Professional Experience
======
* **Subject Matter Expert – AI**, Johns Hopkins University, Jun 2026 – Present, Baltimore, MD  
  Advisor: [Prof. Benjamin Van Durme](https://cs.jhu.edu/~vandurme/) and Dr. William Walden
  * Developed a multi-agent deep-research framework for automated scientific claim verification.
  * Improved memory system with compressed context rendering to mitigate token/context blow-up during long-horizon web research.
  * Implemented a dual-track LLM-as-judge pipeline evaluating final reports and execution traces via claim-specific obligation maps and G-Eval-style staged rubrics.

* **Software Development Engineer**, Beijing Dajia Internet Information Technology (Kuaishou), Jul 2023 – Mar 2025, Beijing, China
  * Built performance analysis, monitoring, and traffic replay tools for large-scale mobile systems, enabling rapid diagnosis of memory and performance issues.
  * Maintained and developed UI components (images, animations, listviews) to support large-scale events on Kuaishou, including Singles' Day and Chinese New Year.
  * Designed ETL pipelines and dashboards to analyze JSVM memory usage, reducing issue attribution time from hours to minutes.
  * Identified and resolved performance and memory inefficiencies in layout, image, animation components and property export; reduced peak memory usage by **56%** and rendering time by **11%** in dynamic stages for e-commerce and local services scenarios.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Programming Languages**: C/C++, Python, Objective-C, JavaScript, Scala, SQL
* **Databases**: MySQL, HBase, PostgreSQL
* **Big Data**: Hive, Hadoop, Spark, Kafka, Flink, PowerBI, Tableau
* **Operating Systems**: Linux
* **ML / SciML**: PyTorch, PINNs, Fourier Neural Operators, Neural ODEs, Hessian analysis
