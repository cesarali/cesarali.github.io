---
title: "Neural Dynamic Focused Topic Model"
collection: publications
permalink: /_publication/neural_dynamic
excerpt: 'Neural Dynamic Topic Models'
date: 2023-06-26
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/26496'
citation: 'Cvejoski, K., Sánchez, R. J., & Ojeda, C. (2023, June). Neural dynamic focused topic model. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 37, No. 11, pp. 12719-12727).'
---

Topic models and all their variants analyse text by learning meaningful representations through word co-occurrences. As pointed out by previous work, such models implicitly assume that the probability of a topic to be active and its proportion within each document are positively correlated. This correlation can be strongly detrimental in the case of documents created over time, simply because recent documents are likely better described by new and hence rare topics. In this work we leverage recent advances in neural variational inference and present an alternative neural approach to the dynamic Focused Topic Model. Indeed, we develop a neural model for topic evolution which exploits sequences of Bernoulli random variables in order to track the appearances of topics, thereby decoupling their activities from their proportions. We evaluate our model on three different datasets (the UN general debates, the collection of NeurIPS papers, and the ACL Anthology dataset) and show that it (i) outperforms state-of-the-art topic models in generalization tasks and (ii) performs comparably to them on prediction tasks, while employing roughly the same number of parameters, and converging about two times faster.

[Download paper here](https://ojs.aaai.org/index.php/AAAI/article/view/26496/26268)



