---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Bias Amplification Enhances Minority Group Performance'
subtitle: 'TMLR, 2024. [PDF](https://arxiv.org/abs/2309.06717)'
summary: 'Neural networks produced by standard training are known to suffer from poor accuracy on rare subgroups despite achieving high accuracy on average, due to the correlations between certain spurious features and labels. Previous approaches based on worst-group loss minimization (e.g. Group-DRO) are effective in improving worse-group accuracy but require expensive group annotations for all the training samples. In this paper, we focus on the more challenging and realistic setting where group annotations are only available on a small validation set or are not available at all. We propose BAM, a novel two-stage training algorithm: in the first stage, the model is trained using a bias amplification scheme via introducing a learnable auxiliary variable for each training sample; in the second stage, we upweight the samples that the bias-amplified model misclassifies, and then continue training the same model on the reweighted dataset. Empirically, BAM achieves competitive performance compared with existing methods evaluated on spurious correlation benchmarks in computer vision and natural language processing. Moreover, we find a simple stopping criterion based on minimum class accuracy difference that can remove the need for group annotations, with little or no loss in worst-group accuracy. We perform extensive analyses and ablations to verify the effectiveness and robustness of our algorithm in varying class and group imbalance ratios.'
authors:
- Gaotang Li*
- Jiarui Liu*
- Wei Hu

pub: 'TMLR, 2024.'
tags:
- Group Robustness
- Spurious Correlation
categories: []
# date: '2023-01-26'
lastmod: 2023-10-06T10:29:07+09:00
featured: true
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: true

projects: []
publication_short: 'TMLR 2024'

links:
- name: Arxiv
  url: https://arxiv.org/abs/2309.06717
---