---
title: "A Proactive Defense Against Model Poisoning Attacks in Federated Learning"
collection: publications
category: manuscripts
permalink: /publication/A-proactive-defense-against-model-poisoning-attacks-in-federated-learning
excerpt: 'Haonan Yan, Chengbo Zheng, Qian Chen, **Xiaoguang Li**, Bin Wang, Hui Li, Xiaodong Lin. (Corresponding authors: Xiaoguang Li, Hui Li)'
date: 2025-01-23
venue: 'IEEE Transactions on Dependable and Secure Computing'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10851419'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Model poisoning attacks greatly jeopardize the application of federated learning (FL). The effectiveness of existing defenses is susceptible to the latest model poisoning attacks, leading to a decrease in prediction accuracy. Besides, these defenses are intractable to distinguish benign outliers from malicious gradients, which further compromises the model generalization. In this work, we propose a novel proactive defense named RECESS against model poisoning attacks. Different from the passive analysis in previous defenses, RECESS proactively queries each participating client with a delicately constructed aggregation gradient, accompanied by the detection of malicious clients according to their responses with higher accuracy. Furthermore, RECESS uses a new trust scoring mechanism to robustly aggregate gradients. Unlike previous methods that score each iteration, RECESS considers clients’ performance correlation across multiple iterations to estimate the trust score, substantially increasing fault tolerance. Finally, we extensively evaluate RECESS on typical model architectures and four datasets under various settings. We also evaluated the defensive effectiveness against other types of poisoning attacks, the sensitivity of hyperparameters, and adaptive adversarial attacks. Experimental results show the superiority of RECESS in terms of reducing accuracy loss caused by the latest model poisoning attacks over five classic and two state-of-the-art defenses.
