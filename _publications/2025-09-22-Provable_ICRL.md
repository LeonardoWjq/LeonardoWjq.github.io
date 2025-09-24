---
title: "Towards Provable Emergence of In-Context Reinforcement Learning"
authors: "<b>Jiuqi Wang</b> , Rohan Chandra, Shangtong Zhang"
collection: publications
permalink: /publication/2025-09-22-Provable_ICRL
excerpt:
note: 
date: 2025-09-22
venue: 'NeurIPS'
paperurl: 'https://arxiv.org/abs/2509.18389'
citation:
abstract: "Typically, a modern reinforcement learning (RL) agent solves a task by updating its neural network parameters to adapt its policy to the task. Recently, it has been observed that some RL agents can solve a wide range of new out-of-distribution tasks without parameter updates after pretraining on some task distribution. When evaluated in a new task, instead of making parameter updates, the pretrained agent conditions its policy on additional input called the context, e.g., the agent's interaction history in the new task. The agent's performance increases as the information in the context increases, with the agent's parameters fixed. This phenomenon is typically called in-context RL (ICRL). The pretrained parameters of the agent network enable the remarkable ICRL phenomenon. However, many ICRL works perform the pretraining with standard RL algorithms. This raises the central question this paper aims to address: Why can the RL pretraining algorithm generate network parameters that enable ICRL? We hypothesize that the parameters capable of ICRL are minimizers of the pretraining loss. This work provides initial support for this hypothesis through a case study. In particular, we prove that when a Transformer is pretrained for policy evaluation, one of the global minimizers of the pretraining loss can enable in-context temporal difference learning."
---