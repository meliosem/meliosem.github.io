---
title: "Robust Single-message Shuffle Differential Privacy Protocol for Accurate Distribution Estimation"
collection: publications
category: conferences
permalink: /publication/Robust-Single-message-Shuffle-Differential-Privacy-Protocol-for-Accurate-Distribution-Estimation
excerpt: '**Xiaoguang Li**, Hanyi Wang, Yaowei Huang, Jungang Yang, Qingqing Ye, Haonan Yan, Ke Pan, Zhe Sun, Hui Li'
date: 2026-02-24
venue: 'IEEE International Conference on Data Engineering (ICDE)'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://faculty.xidian.edu.cn/LIXIAOGUANG/en/lwcg/455283/content/303105.htm#lwcg'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Shuffler-based differential privacy (shuffle-DP) is a privacy paradigm providing high utility by involving a shuffler to permute noisy report from users. Existing shuffle-DP protocols mainly focus on the design of shuffler-based categorical frequency oracle (SCFO) for frequency estimation on categorical data. However, numerical data is a more prevalent type and many real-world applications depend on the estimation of data distribution with ordinal nature. In this paper, we study the distribution estimation under pure shuffle model, which is a prevalent shuffle-DP framework without strong security assumptions. We initially attempt to transplant existing SCFOs and the na\"ive distribution recovery technique to this task, and demonstrate that these baseline protocols cannot simultaneously achieve outstanding performance in three metrics: 1) utility, 2) message complexity; and 3) robustness to data poisoning attacks. Therefore, we further propose a novel single-message *adaptive shuffler-based piecewise* (ASP) protocol with high utility and robustness. In ASP, we first develop a randomizer by parameter optimization using our proposed tighter bound of mutual information. We also design an *Expectation Maximization with Adaptive Smoothing* (EMAS) algorithm to accurately recover distribution with enhanced robustness. To quantify robustness, we propose a new evaluation framework to examine robustness under different attack targets, enabling us to comprehensively understand the protocol resilience under various adversarial scenarios. Extensive experiments demonstrate that ASP outperforms baseline protocols in all three metrics. Especially under small $\epsilon$ values, ASP achieves an order of magnitude improvement in utility with minimal message complexity, and exhibits over threefold robustness compared to baseline methods.
