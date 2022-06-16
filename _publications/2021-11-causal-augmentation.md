---
title: "Causal augmentation for causal sentence classification"
collection: publications
permalink: /publications/2021-11-causal-augmentation
excerpt: 'Scarcity of annotated causal texts leads to poor robustness when training state-of-the-art language models for causal sentence classification. In particular, we found that models misclassify on augmented sentences that have been negated or strengthened with respect to its causal meaning. This is worrying since minor linguistic differences in causal sentences can have disparate meanings. Therefore, we propose the generation of counterfactual causal sentences by creating contrast sets (Gardner et al., 2020) to be included during model training. We experimented on two model architectures and predicted on two out-of-domain corpora. While our strengthening schemes proved useful in improving model performance, for negation, regular edits were insufficient. Thus, we also introduce heuristics like shortening or multiplying root words of a sentence. By including a mixture of edits when training, we achieved performance improvements beyond the baseline across both models, and within and out of corpus’ domain, suggesting that our proposed augmentation can also help models generalize.'
date: 2021
venue: 'First Workshop on Causal Inference and NLP'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Fiona Anting Tan, Devamanyu Hazarika, See-Kiong Ng, Soujanya Poria, and Roger Zimmermann. Causal augmentation for causal sentence classification. In Proceedings of the First Workshop on Causal Inference and NLP, pages 1–20, Punta Cana, Dominican Republic, November 2021. Association for Computational Linguistics. doi: 10.18653/v1/2021.cinlp-1.1. URL https://aclanthology.org/2021.cinlp-1.1'
---

[Download paper here](https://aclanthology.org/2021.cinlp-1.1)