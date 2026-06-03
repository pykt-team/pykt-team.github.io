---
layout: post
title: 'DenoiseKT: Denoised Attention and Question-Augmented Representations for Knowledge Tracing'
date: 2025-08-31T00:00:00.000+00:00
tags: model
categories: []
author: ''
post_image: "/assets/images/posts/denoisekt.png"
post_format: ''
trending: true

---
We added DenoiseKT into our pyKT package.

The link is [here](https://pykt-toolkit.readthedocs.io/en/latest/models.html#denoisekt) and the API is [here](https://pykt-toolkit.readthedocs.io/en/latest/pykt.models.html#module-pykt.models.denoisekt).

Original paper can be found at Deng, Jiwei et al. "Denoised Attention and Question-Augmented Representations for Knowledge Tracing." [Proceedings of the 34th International Joint Conference on Artificial Intelligence, pp. 9619-9627, 2025.
](https://doi.org/10.24963/ijcai.2025/1069)


Title: Denoised Attention and Question-Augmented Representations for Knowledge Tracing

Abstract: Knowledge tracing (KT) is an essential task in online education systems. It aims to predict the future performance of students based on their historical learning interaction data. Despite significant advancements in attention-based KT models, they still face some limitations: inaccurate input representation and excessive student forgetting modeling. These limitations often lead to the attention noise problem: the model assigns non-negligible attention weight to some information that is cognitively irrelevant in nature, thereby generating interference signals. To address this problem, we propose a novel KT model, i.e., DenoiseKT. DenoiseKT effectively models the difficulty of the questions and utilizes graph neural network to capture the complex relationship between questions, thereby refining the representations of input features. Additionally, the denoised attention mechanism introduces a weight factor to reduce the model's attention weight distribution on irrelevant information. We extensively compare DenoiseKT with 22 state-of-the-art KT models on 4 widely-used public datasets. Experimental results show that DenoiseKT can effectively solve the attention noise problem and outperform other models. The source code of DenoiseKT is available at https://pykt.org.
