---
title: "PokeeResearch: Effective Deep Research via Reinforcement Learning from AI Feedback and Robust Reasoning Scaffold"
authors: "Yi Wan*, <b>Jiuqi Wang</b>*, Liam Li, Jinsong Liu, Ruihao Zhu, Zheqing Zhu"
collection: publications
permalink: /publication/2025-10-17-PokeeResearch
excerpt:
note: 
date: 2025-10-17
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2510.15862'
citation:
abstract: "Tool-augmented large language models (LLMs) are emerging as deep research agents—systems that decompose complex queries, retrieve external evidence, and synthesize grounded responses. Yet current
agents remain limited by shallow retrieval, weak alignment metrics, and brittle tool-use behavior. We introduce PokeeResearch-7B, a 7B-parameter deep research agent built under a unified reinforcement learning framework for robustness, alignment, and scalability. PokeeResearch-7B is trained by a Reinforcement Learning from AI Feedback (RLAIF) framework to optimize policies using LLM-based reward signals that capture factual accuracy, citation faithfulness, and instruction adherence. A chain-of-thought–driven multi-call reasoning scaffold further enhances robustness through adaptive recovery from tool failures and self-verification on generated answers. At test time, multiple research threads are executed independently and synthesized to produce the best answer. Among 10 popular deep research benchmarks, PokeeResearch-7B achieves state-of-the-art performance among 7B-scale deep research agents. This highlights that careful reinforcement learning and reasoning design can produce efficient, resilient, and research-grade AI agents. The model and inference code is open-sourced under Apache 2.0 license at <a href="https://github.com/Pokee-AI/PokeeResearchOSS">https://github.com/Pokee-AI/PokeeResearchOSS</a>."
---