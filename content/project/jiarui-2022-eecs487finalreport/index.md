---
title: 'FAD: Feature Alignment Discriminator for Abstractive Text Summarization'
summary: ''
tags:
- NLP
pub: '**EECS-487 Natural language processing course project.**'
date: "2022-04-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
# external_link: https://example.org

image:
  caption: Model structure
  focal_point: Smart

abstract: 'Existing abstractive approaches for automatic text summarization have shown low preciseness and coherence in their generated summaries. In this project, we present a special fine-tuning process for text generators like BART with the FAD, the Feature Alignment Discriminator. We propose that with the token replacement detecting mechanism in feature space, the FAD greatly addresses problems of  discreteness in adversarial learning for NLP and better captures the word distribution of the original texts. With extensive experiments, we find that using the first layer of BART decoder as the feature results in better performance. It is also shown that on the DailyMail/CNN dataset, that our FAD model outperforms BART base model in by 0.2 perplexity score and 0.3-0.5\% ROUGE score and matches the S.O.T.A R-Drop model. We claim that the FAD structure has shown great applicability and can be used for other general text generation tasks.'
url_pdf: project/jiarui-2022-eecs487finalreport/report.pdf
---
