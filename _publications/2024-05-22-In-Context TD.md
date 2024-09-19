---
title: "Transformers Learn Temporal Difference Methods for In-Context Reinforcement Learning"
authors: "<b>Jiuqi Wang</b>* , Ethan Blaser*, Hadi Daneshmand, Shangtong Zhang"
collection: publications
permalink: /publication/2024-05-22-In-Context TD
excerpt:
note: "Contributed talk at the <i>RLC Workshop on Training Agents with Foundation Models</i>, 2024.<br>
       Spotlight Award at the <i>ICML Workshop on In-Context Learning</i>, 2024."
date: 2024-05-22
venue: 'arXiv'
paperurl: 'https://www.arxiv.org/abs/2405.13861'
citation:
abstract: "In-context learning refers to the learning ability of a model during inference time without adapting its parameters. The input (i.e., prompt) to the model (e.g., transformers) consists of both a context (i.e., instance-label pairs) and a query instance. The model is then able to output a label for the query instance according to the context during inference. A possible explanation for in-context learning is that the forward pass of (linear) transformers implements iterations of gradient descent on the instance-label pairs in the context. In this paper, we prove by construction that transformers can also implement temporal difference (TD) learning in the forward pass, a phenomenon we refer to as in-context TD. We demonstrate the emergence of in-context TD after training the transformer with a multi-task TD algorithm, accompanied by theoretical analysis. Furthermore, we prove that transformers are expressive enough to implement many other policy evaluation algorithms in the forward pass, including residual gradient, TD with eligibility trace, and average-reward TD."
---