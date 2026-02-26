---
title: "Fine-grained poisoning attack to local differential privacy protocols for mean and variance estimation"
collection: publications
category: conferences
permalink: /publication/Fine-grained-poisoning-attack-to-local-differential-privacy-protocols-for-mean-and-variance-estimation
excerpt: '**Xiaoguang Li**, Ninghui Li, Wenhai Sun, Neil Zhenqiang Gong, Hui Li'
date: 2023-08-09
venue: 'USENIX Security Symposium'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.usenix.org/system/files/usenixsecurity23-li-xiaoguang.pdf'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Although local differential privacy (LDP) protects individual users' data from inference by an untrusted data curator, recent studies show that an attacker can launch a data poisoning attack from the user side to inject carefully-crafted bogus data into the LDP protocols in order to maximally skew the final estimate by the data curator.

In this work, we further advance this knowledge by proposing a new fine-grained attack, which allows the attacker to fine-tune and simultaneously manipulate mean and variance estimations that are popular analytical tasks for many real-world applications. To accomplish this goal, the attack leverages the characteristics of LDP to inject fake data into the output domain of the local LDP instance. We call our attack the output poisoning attack (OPA). We observe a security-privacy consistency where a small privacy loss enhances the security of LDP, which contradicts the known security-privacy trade-off from prior work. We further study the consistency and reveal a more holistic view of the threat landscape of data poisoning attacks on LDP. We comprehensively evaluate our attack against a baseline attack that intuitively provides false input to LDP. The experimental results show that OPA outperforms the baseline on three real-world datasets. We also propose a novel defense method that can recover the result accuracy from polluted data collection and offer insight into the secure LDP design.