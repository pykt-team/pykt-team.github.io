---
layout: post
title: 'Dtransformer: Stable Knowledge Tracing with Diagnostic Transformer'
date: 2024-03-08T16:00:00.000+00:00
tags: model
categories: []
author: ''
post_image: "/assets/images/posts/dtransformer.png"
post_format: ''
trending: true

---
We added Dtransformer into our pyKT package.

The link is [here](https://pykt-toolkit.readthedocs.io/en/latest/models.html#dtransformer).

Original paper can be found at [Yin, Yu, et al. “Tracing Knowledge Instead of Patterns: Stable Knowledge Tracing with Diagnostic Transformer.” Proceedings of the ACM Web Conference. 2023.
](https://dl.acm.org/doi/abs/10.1145/3543507.3583255)

Title: Tracing Knowledge Instead of Patterns: Stable Knowledge Tracing with Diagnostic Transformer


Abstract:Knowledge Tracing (KT) aims at tracing the evolution of the knowledge states along the learning process of a learner. It has become a crucial task for online learning systems to model the learning process of their users, and further provide their users a personalized learning guidance. However, recent developments in KT based on deep neural networks mostly focus on increasing the accuracy of predicting the next performance of students. We argue that current KT modeling, as well as training paradigm, can lead to models tracing patterns of learner’s learning activities, instead of their evolving knowledge states. In this paper, we propose a new architecture, Diagnostic Transformer (DTransformer), along with a new training paradigm, to tackle this challenge. With DTransformer, we build the architecture from question-level to knowledge-level, explicitly diagnosing learner’s knowledge proficiency from each question mastery states. We also propose a novel training algorithm based on contrastive learning that focuses on maintaining the stability of the knowledge state diagnosis. Through extensive experiments, we will show that with its understanding of knowledge state evolution, DTransformer achieves a better performance prediction accuracy and more stable knowledge state tracing results. We will also show that DTransformer is less sensitive to specific patterns with case study. We open-sourced our code and data at https://github.com/yxonic/DTransformer.
