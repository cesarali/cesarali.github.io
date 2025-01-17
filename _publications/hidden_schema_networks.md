---
title: "Hidden Schema Networks"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Latent representations for Reasoning of Large Language Models'
date: 2023-07-01
venue: 'Association for Computational Linguistics'
paperurl: 'https://aclanthology.org/2023.acl-long.263/'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Large, pretrained language models infer powerful representations that encode rich semantic and syntactic content, albeit implicitly. In this work we introduce a novel neural language model that enforces, via inductive biases, explicit relational structures which allow for compositionality onto the output representations of pretrained language models. Specifically, the model encodes sentences into sequences of symbols (composed representations), which correspond to the nodes visited by biased random walkers on a global latent graph, and infers the posterior distribution of the latter. We first demonstrate that the model is able to uncover ground-truth graphs from artificially generated datasets of random token sequences. Next, we leverage pretrained BERT and GPT-2 language models as encoder and decoder, respectively, to infer networks of symbols (schemata) from natural language datasets. Our experiments show that (i) the inferred symbols can be interpreted as encoding different aspects of language, as e.g. topics or sentiments, and that (ii) GPT-2-like models can effectively be conditioned on symbolic representations. Finally, we explore training autoregressive, random walk “reasoning” models on schema networks inferred from commonsense knowledge databases, and using the sampled paths to enhance the performance of pretrained language models on commonsense If-Then reasoning tasks.

[Download paper here](https://aclanthology.org/2023.acl-long.263.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).
