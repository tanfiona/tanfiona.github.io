---
title: "Causal Augmentation for Causal Sentence Classification"
collection: publications
permalink: /publication/2021-11-01-causal-augment
excerpt: 'Scarcity of annotated causal texts leads to poor robustness when training state-of-the-art language models for causal sentence classification. In particular, we found that models misclassify on augmented sentences that have been negated or strengthened with respect to its causal meaning. This is worrying since minor linguistic differences in causal sentences can have disparate meanings. Therefore, we propose the generation of counterfactual causal sentences by creating contrast sets (Gardner et al., 2020) to be included during model training. We experimented on two model architectures and predicted on two out-of-domain corpora. While our strengthening schemes proved useful in improving model performance, for negation, regular edits were insufficient. Thus, we also introduce heuristics like shortening or multiplying root words of a sentence. By including a mixture of edits when training, we achieved performance improvements beyond the baseline across both models, and within and out of corpus’ domain, suggesting that our proposed augmentation can also help models generalize.'
date: 2021-11-01
venue: 'First Workshop on Causal Inference and NLP'
paperurl: 'https://aclanthology.org/2021.cinlp-1.1'
citation: 'Fiona Anting Tan, Devamanyu Hazarika, See-Kiong Ng, Soujanya Poria, and Roger Zimmermann. Causal augmentation for causal sentence classification. In Proceedings of the First Workshop on Causal Inference and NLP, pages 1–20, Punta Cana, Dominican Republic, November 2021. Association for Computational Linguistics. doi: 10.18653/v1/2021.cinlp-1.1.'
---

<img src='../images/posters/CausalAugment_CINLP_2021_Presentation_POSTER.png' width=800>


<a href='https://aclanthology.org/2021.cinlp-1.1'>Download paper here</a>

<a href='../files/slides/CausalAugment_CINLP_2021.pdf'>Download presentation slides here</a>

<a href='https://github.com/tanfiona/CausalAugment'>Visit our Github respository here</a>

<h2>Abstract</h2>
Scarcity of annotated causal texts leads to poor robustness when training state-of-the-art language models for causal sentence classification. In particular, we found that models misclassify on augmented sentences that have been negated or strengthened with respect to its causal meaning. This is worrying since minor linguistic differences in causal sentences can have disparate meanings. Therefore, we propose the generation of counterfactual causal sentences by creating contrast sets (Gardner et al., 2020) to be included during model training. We experimented on two model architectures and predicted on two out-of-domain corpora. While our strengthening schemes proved useful in improving model performance, for negation, regular edits were insufficient. Thus, we also introduce heuristics like shortening or multiplying root words of a sentence. By including a mixture of edits when training, we achieved performance improvements beyond the baseline across both models, and within and out of corpus’ domain, suggesting that our proposed augmentation can also help models generalize.
