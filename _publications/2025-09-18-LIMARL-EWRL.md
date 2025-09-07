---
title: "Latent Inference for Effective Multi-Agent Reinforcement Learning under Partial Observability"
collection: workshop
permalink: /publication/2025-09-18-LIMARL-EWRL
date: 2025-09-18
venue: 'European Workshop on Reinforcement Learning (EWRL)'
paperurl: 'https://openreview.net/pdf?id=PHoq8zmFu8'
category: "workshop"

---
Salma Kharrat, Fares Fourati, Mohamed-Slim Alouini,  Marco Canini, & Vaneet Aggarwal

## Abstract
Partial observability remains a core challenge in cooperative multi-agent reinforcement learning (MARL), often causing poor coordination and suboptimal policies.
We show that state-of-the-art methods fail even in simple settings under partial
observability. To address this, we propose LIMARL, a latent-inference framework that augments centralized training with decentralized execution (CTDE) via
structured latent representations. LIMARL integrates (i) a state representation
module that learns compact global state embeddings, and (ii) a recurrent inference
module that enables agents to recover these embeddings from local histories. We
provide theoretical analysis on sufficiency and robustness under partial observability. Empirically, LIMARL outperforms strong baselines in diagnostic tasks
and challenging SMAC and SMACv2 scenarios, demonstrating better performance
and faster convergence. Our results highlight latent inference as an effective and
scalable solution for partially observable MARL.

[[PDF]](https://openreview.net/pdf?id=PHoq8zmFu8)