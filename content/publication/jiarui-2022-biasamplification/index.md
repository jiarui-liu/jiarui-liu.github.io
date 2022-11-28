---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Bias Amplification Improves Worst-Group Accuracy without Group Information'
subtitle: ''
summary: ''
authors:
- Gaotang Li
- admin
- Wei Hu
author_notes:
- "Equal contribution"
- "Equal contribution"
pub: '*Submitted to ICLR 2023.*'
tags:
- Group Robustness
- Spurious Correlation
categories: []
date: '2022-09-28'
# lastmod: 2022-11-25T10:29:07+09:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
# publishDate: '2022-08-17T12:48:03.028141Z'
# publication_types:
# - '3'
abstract: 'We propose BAM, a novel two-stage training algorithm that first trains a model using a *bias amplification* scheme by introducing a learnable instance-wise *auxiliary variable* together with squared loss and upweights the misclassified samples, and then continues training the same model on the reweighted dataset. Empirically, BAM leads to consistent improvement over its counterparts in worst-group accuracy, resulting in state-of-the-art performance in spurious correlation benchmarks in computer vision and natural language processing. Moreover, we find a simple stopping criterion that completely removes the need for group annotations, with little or no loss in worst-group accuracy.'
publication: ''
url_pdf: https://openreview.net/pdf?id=TSqRwmrRiOn
---