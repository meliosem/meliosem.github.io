---
title: "A Log-Likelihood Chain Framework for Defending Against LDP Data Poisoning Attacks"
collection: publications
category: manuscripts
permalink: /publication/A-Log-Likelihood-Chain-Framework-for-Defending-Against-LDP-Data-Poisoning-Attacks
excerpt: 'Xiaoguang Li, Yuxin Wen, Yuchen Wang, Haonan Yan, Yahong Chen, Zhe Sun, Hui Li'
date: 2025-12-31
venue: 'IEEE Transactions on Knowledge and Data Engineering'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11271534'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Local differential privacy (LDP) provides strict privacy guarantee in a distributed environment. Recent studies demonstrated that LDP protocols are vulnerable to data poisoning attacks where an attacker can manipulate the perturbed result on the local side and send bogus data to skew the final estimate on the server. Unfortunately, existing attack detections do not create an effective attack indicator and rely on particular characteristics of LDP protocols. As a result, they typically exhibit limited detection performance. In this paper, we use log-likelihood as the attack indicator and propose a chain-style detection to enhance the detection effectiveness, in which the attack impact could propagate along the chain and exhibit clear anomaly signal even under stealthy attack scenarios. The experimental results show that our detection consistently outperforms the existing methods. Using four datasets containing categorical and numerical data separately, our detection achieves an F1 score exceeding 96% in most cases. It even remains above 0.9 under stealthy attack settings, outperforming the state-of-the-art detection by up to 0.25.