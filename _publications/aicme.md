---
title: "Amortized In-Context Mixed Effect Transformer Models: A Zero-Shot Approach for Pharmacokinetics"
collection: publications
permalink: /publication/aicme
excerpt: 'Prior Fitted Neural Operators for Pharmacokinetic Modelling'
date: 2025-08-21
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2508.15659'
citation: 'C. A. Ojeda Marin, W. Huisinga, P. Kawele, N. Hartung. (2025). "Amortized In-Context Mixed Effect Transformer Models: A Zero-Shot Approach for Pharmacokinetics." <i>arXiv preprint</i> arXiv:2508.15659.'

---

Accurate dose-response forecasting under sparse sampling is central to precision pharmacotherapy. We present the Amortized In-Context Mixed-Effect Transformer (AICMET) model, a transformer-based latent-variable framework that unifies mechanistic compartmental priors with amortized in-context Bayesian inference. AICMET is pre-trained on hundreds of thousands of synthetic pharmacokinetic trajectories with Ornstein-Uhlenbeck priors over the parameters of compartment models, endowing the model with strong inductive biases and enabling zero-shot adaptation to new compounds. At inference time, the decoder conditions on the collective context of previously profiled trial participants, generating calibrated posterior predictions for newly enrolled patients after a few early drug concentration measurements. This capability collapses traditional model-development cycles from weeks to hours while preserving some degree of expert modelling. Experiments across public datasets show that AICMET attains state-of-the-art predictive accuracy and faithfully quantifies inter-patient variability -- outperforming both nonlinear mixed-effects baselines and recent neural ODE variants. Our results highlight the feasibility of transformer-based, population-aware neural architectures as offering a new alternative for bespoke pharmacokinetic modeling pipelines, charting a path toward truly population-aware personalized dosing regimens.

[Download paper here](https://arxiv.org/pdf/2508.15659)

