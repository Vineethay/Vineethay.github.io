---
layout: archive
title: 
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

<!-- {% include base_path %} -->

Cross-dataset Facial Expression Recognition
======
Facial expression recognition (FER) models trained on one dataset (source) usually do not perform well on a different dataset (target) due to the implicit domain shift between different datasets. In addi- tion, FER data is naturally highly imbalanced, with a majority of the samples belonging to few expressions like neutral, happy and relatively fewer samples coming from expressions like disgust, fear, etc., which makes the FER task even more challenging. This class imbalance of the source and target data (which may be different), along with other factors like similarity of few expressions, etc., can result in unsatisfactory target classification performance due to confusion between the different classes. In this work, we propose an integrated module, termed DIFC, which can not only handle the source Data Imbalance, but also the Feature Confusion of the target data for improved classification of the target expressions. We integrate this DIFC module with an existing unsupervised domain adaptation (UDA) approach to handle the domain shift and show that the proposed simple yet effective module can result in signif- icant performance improvement on four benchmark datasets for cross-dataset FER task. We also show that the proposed module works across different architectures and can be used with other UDA baselines to further boost their performance.
