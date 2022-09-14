---
title: "Certified Defences Against Adversarial Patch Attacks on Semantic Segmentation"
collection: publications
permalink: /publication/2022-09-13-Certified-defences
excerpt: 'tldr: we mask out areas and use a voring mechanism to defend certifiably against patch attacks.'
date: 2022-09-13
venue: 'Preprint'
paperurl: 'https://arxiv.org/abs/2209.05980'
citation: 'Maksym Yatsura, Kaspar Sakmann, N. Grace Hua, Matthias Hein, Jan Hendrik Metzen (2022). 
&quot;Certified Defences Against Adversarial Patch Attacks on Semantic Segmentation.&quot; <i>arXiv:2209.05980</i>'
---

Adversarial patch attacks are an emerging security threat for real world deep learning applications. 
We present Demasked Smoothing, the first approach (up to our knowledge) to certify the robustness of 
semantic segmentation models against this threat model. Previous work on certifiably defending against 
patch attacks has mostly focused on image classification task and often required changes in the model 
architecture and additional training which is undesirable and computationally expensive. In Demasked 
Smoothing, any segmentation model can be applied without particular training, fine-tuning, or restriction 
of the architecture. Using different masking strategies, Demasked Smoothing can be applied both for 
certified detection and certified recovery. In extensive experiments we show that Demasked Smoothing 
can on average certify 64% of the pixel predictions for a 1% patch in the detection task and 48% 
against a 0.5% patch for the recovery task on the ADE20K dataset.


[Download paper here](https://arxiv.org/pdf/2209.05980)

