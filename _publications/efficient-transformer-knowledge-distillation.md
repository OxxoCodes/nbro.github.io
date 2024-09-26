---
title: "Efficient Transformer Knowledge Distillation: A Performance Review"
collection: publications
category: manuscripts
permalink: /research/2023-11-22
excerpt: 'This paper discusses the distillation of long-context, efficient attention BERT-based models to yield models that are smaller, faster, and cheaper to deploy.'
date: 2023-11-22
venue: 'Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'https://arxiv.org/pdf/2311.13657.pdf'
citation: 'Brown, Nathan and Williamson, Ashton and Anderson, Tahj and Lawrence, Logan. (2023). &quot;Efficient Transformer Knowledge Distillation: A Performance Review&quot; <i>Empirical Methods in Natural Language Processing</i>.'
---

As pretrained transformer language models continue to achieve state-of-the-art performance, the Natural Language Processing community has pushed for advances in model compression and efficient attention mechanisms to address high computational requirements and limited input sequence length. Despite these separate efforts, no investigation has been done into the intersection of these two fields. In this work, we provide an evaluation of model compression via knowledge distillation on efficient attention transformers. We provide cost-performance trade-offs for the compression of state-of-the-art efficient attention architectures and the gains made in performance in comparison to their full attention counterparts. Furthermore, we introduce a new long-context Named Entity Recognition dataset, GONERD, to train and test the performance of NER models on long sequences. We find that distilled efficient attention transformers can preserve a significant amount of original model performance, preserving up to 98.6% across short-context tasks (GLUE, SQUAD, CoNLL-2003), up to 94.6% across long-context Question-and-Answering tasks (HotpotQA, TriviaQA), and up to 98.8% on long-context Named Entity Recognition (GONERD), while decreasing inference times by up to 57.8%. We find that, for most models on most tasks, performing knowledge distillation is an effective method to yield high-performing efficient attention models with low costs. 

[Download paper here](https://arxiv.org/pdf/2311.13657.pdf)