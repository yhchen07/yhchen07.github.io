---
title: "Wireless Traffic Prediction with Scalable Gaussian Process: Framework, Algorithms, and Verification"
collection: publications
permalink: /publications/JSAC19
venue: "IEEE Journal on Selected Areas in Communications (JSAC)"
date: March, 2019
Authors: '<b>Yue Xu</b>, Feng Yin, Wenjun Xu, Jiaru Lin, Shuguang Cui.'
---

[[IEEE Link]](<https://ieeexplore.ieee.org/document/8664622>)
[[Arxiv Link]](<https://arxiv.org/abs/1902.04763>)

## Abstract
The cloud radio access network (C-RAN) is a promising paradigm to meet the stringent requirements of the fifth generation (5G) wireless systems. Meanwhile, wireless traffic prediction is a key enabler for C-RANs to improve both the spectrum efficiency and energy efficiency through load-aware network managements. This paper proposes a scalable Gaussian process (GP) framework as a promising solution to achieve large-scale wireless traffic prediction in a cost-efficient manner. 
Our contribution is three-fold. 
First, to the best of our knowledge, this paper is the first to empower GP regression with the alternating direction method of multipliers (ADMM) for parallel hyper-parameter optimization in the training phase, where such a scalable training framework well balances the local estimation in baseband units (BBUs) and information consensus among BBUs in a principled way for large-scale executions. 
Second, in the prediction phase, we fuse local predictions obtained from the BBUs via a cross-validation based optimal strategy, which demonstrates itself to be reliable and robust for general regression tasks. Moreover, such a cross-validation based optimal fusion strategy is built upon a well acknowledged probabilistic model to retain the valuable closed-form GP inference properties. 
Third, we propose a C-RAN based scalable wireless prediction architecture, where the prediction accuracy and the time consumption can be balanced by tuning the number of the BBUs according to the real-time system demands.
Experimental results show that our proposed scalable GP model can outperform the state-of-the-art approaches considerably, in terms of wireless traffic prediction performance.
