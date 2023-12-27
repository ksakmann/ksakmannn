---
title: "Anomaly-Aware Semantic Segmentation via Style-Aligned OoD Augmentation"
collection: publications
permalink: /publication/2023-08-19-Anomaly-Aware
excerpt: 'tldr: we use an outlier exposure pipeline to boost anomaly segmentation performance with style alignment'
date: 2023-08-19
venue: 'ICCV Bravo Workshop'
paperurl: 'https://arxiv.org/abs/2308.09965'
citation: 'Dan Zhang, Kaspar Sakmann, William Beluch, Robin Hutmacher, Yumeng Li (2023). 
&quot;Anomaly-Aware Semantic Segmentation via Style-Aligned OoD Augmentation.&quot; <i>arXiv:2308.09965</i>'
---

Within the context of autonomous driving, encountering unknown objects becomes inevitable during deployment in the open world. Therefore, it is crucial to equip standard semantic segmentation models with anomaly awareness. Many previous approaches have utilized synthetic out-of-distribution (OoD) data augmentation to tackle this problem. In this work, we advance the OoD synthesis process by reducing the domain gap between the OoD data and driving scenes, effectively mitigating the style difference that might otherwise act as an obvious shortcut during training. Additionally, we propose a simple fine-tuning loss that effectively induces a pre-trained semantic segmentation model to generate a ``none of the given classes" prediction, leveraging per-pixel OoD scores for anomaly segmentation. With minimal fine-tuning effort, our pipeline enables the use of pre-trained models for anomaly segmentation while maintaining the performance on the original task.

[Download paper here](https://arxiv.org/pdf/2308.09965)

