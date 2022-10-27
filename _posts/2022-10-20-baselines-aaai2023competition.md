---
layout: post
title: Baselines for Global Knowledge Tracing Challenge 
date: 2022-10-20 16:00:00 +0000
tags: ''
categories: []
author: ''
# post_image: "/assets/images/posts/update.jpeg"
post_format: ''
trending: true
---

## Baselines for Global Knowledge Tracing Challenge

We have used pyKT to run **DKT** and **AKT** on the aforementioned training data and evaluate on our public test sets. All these approaches are purely trained with question/KC ids and student responses without any auxiliary information, such as question content. The results are used as baseline results for this competition:

| Model    | Non-Accumulative | Accumulative |
| :------- | :--------------: | :----------: |
| DKT      |      0.6801      |    0.7086    |
| AKT      |      0.7812      |    0.7692    |
| Majority |      0.7381      |      -       |


Practically, there are two different approaches, i.e., **accumulative prediction** and **non-accumulative prediction**. The accumulative prediction approach uses the last predicted values for the current prediction while the non-accumulative prediction predicts all future values all at once. Details are discussed in the pyKT paper [^1].


Codes and detailed instructions can find in [here](https://github.com/pykt-team/pykt-toolkit/tree/main/examples/competitions/aaai2023_competition).

[^1]: Liu, Zitao, et al. "pyKT: A Python Library to Benchmark Deep Learning based Knowledge Tracing Models." Thirty-sixth Conference on Neural Information Processing Systems Datasets and Benchmarks Track.