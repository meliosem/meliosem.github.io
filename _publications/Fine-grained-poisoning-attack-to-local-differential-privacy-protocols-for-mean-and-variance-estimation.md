---
title: "Fine-grained poisoning attack to local differential privacy protocols for mean and variance estimation"
collection: publications
category: conferences
permalink: /publication/On-the-Robustness-of-LDP-Protocols-for-Numerical-Attributes-under-Data-Poisoning-Attacks
excerpt: 'Xiaoguang Li, Zitao Li, Ninghui Li, Wenhai Sun'
date: 2025-02-28
venue: 'Network and Distributed System Security (NDSS) Symposium'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.ndss-symposium.org/wp-content/uploads/2025-1521-paper.pdf'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Recent studies reveal that local differential privacy (LDP) protocols are vulnerable to data poisoning attacks where an attacker can manipulate the final estimate on the server by leveraging the characteristics of LDP and sending carefully crafted data from a small fraction of controlled local clients. This vulnerability raises concerns regarding the robustness and reliability of LDP in hostile environments.

In this paper, we conduct a systematic investigation of the robustness of state-of-the-art LDP protocols for numerical attributes, i.e., categorical frequency oracles (CFOs) with binning and consistency, and distribution reconstruction. We evaluate protocol robustness through an attack-driven approach and propose new metrics for cross-protocol attack gain measurement. The results indicate that Square Wave and CFO-based protocols in the textit{Server} setting are more robust against the attack compared to the CFO-based protocols in the textit{User} setting. Our evaluation also unfolds new relationships between LDP security and its inherent design choices. We found that the hash domain size in local-hashing-based LDP has a profound impact on protocol robustness beyond the well-known effect on utility. Further, we propose a textit{zero-shot attack detection} by leveraging the rich reconstructed distribution information. The experiment show that our detection significantly improves the existing methods and effectively identifies data manipulation in challenging scenarios.