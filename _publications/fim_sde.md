---
title: "In-Context Learning of Stochastic Differential Equations with Foundation Inference Models"
collection: publications
permalink: /publication/fim_sde
excerpt: 'In context learning for SDE'
date: 2025-02-26
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2502.19049'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Stochastic differential equations (SDEs) describe dynamical systems where de-
terministic flows, governed by a drift function, are superimposed with random
fluctuations, dictated by a diffusion function. The accurate estimation (or dis-
covery) of these functions from data is a central problem in machine learning,
with wide application across the natural and social sciences. Yet current solutions
either rely heavily on prior knowledge of the dynamics or involve intricate training
procedures. We introduce FIM-SDE (Foundation Inference Model for SDEs), a
pretrained recognition model that delivers accurate in-context (or zero-shot) estima-
tion of the drift and diffusion functions of low-dimensional SDEs, from noisy time
series data, and allows rapid finetuning to target datasets. Leveraging concepts from
amortized inference and neural operators, we (pre)train FIM-SDE in a supervised
fashion to map a large set of noisy, discretely observed SDE paths onto the space
of drift and diffusion functions. We demonstrate that FIM-SDE achieves robust
in-context function estimation across a wide range of synthetic and real-world
processes — from canonical SDE systems (e.g. double-well dynamics or weakly
perturbed Lorenz attractors) to stock price recordings and oil-price and wind-speed
fluctuations — while matching the performance of symbolic, Gaussian process and
Neural SDE baselines trained on the target datasets. When finetuned to the target
processes, we show that FIM-SDE consistently outperforms all these baselines.
Our pretrained model, repository and tutorials are available online.

[Download paper here](https://arxiv.org/pdf/2502.19049)

