---
title: "ACING: Actor-Critic for Instruction Learning in Black-Box LLMs"
collection: workshop
permalink: /publication/2025-09-17-acing-EWRL
date: 2025-09-17
venue: 'European Workshop on Reinforcement Learning (EWRL)'
paperurl: 'https://arxiv.org/abs/2411.12736'
category: "workshop"
---
Salma Kharrat, Fares Fourati, & Marco Canini

## Abstract
The effectiveness of Large Language Models (LLMs) in solving tasks depends significantly on the quality of their instructions, which often require substantial human effort to craft. This underscores the need for automated instruction optimization. However, optimizing instructions is particularly challenging when working with black-box LLMs, where model parameters and gradients are inaccessible. We introduce ACING, an actor-critic reinforcement learning framework that formulates instruction optimization as a stateless, continuous-action problem, enabling exploration of infinite instruction spaces using only black-box feedback. ACING automatically discovers prompts that outperform human-written prompts in 76\% of instruction-induction tasks, with gains of up to 33 points and a 10-point median improvement over the best automatic baseline in 33 tasks spanning instruction-induction, summarization, and chain-of-thought reasoning. Extensive ablations highlight its robustness and efficiency.

[[PDF]](https://arxiv.org/pdf/2411.12736), [[Code]](https://github.com/salmakh1/ACING)