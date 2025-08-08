---
title: Enhancing Lung Segmentation Algorithms to Ensure Inclusion of Juxtapleural
  Nodules
authors:
- Luoting Zhuang
- Seyed Mohammad Hossein Tabatabaei
- Ashley E. Prosper
- William Hsu
date: '2025-04-01'
publishDate: '2025-08-08T01:08:53.770647Z'
publication_types:
- paper-conference
publication: '*2025 IEEE 22nd International Symposium on Biomedical Imaging (ISBI)*'
doi: 10.1109/ISBI60581.2025.10981085
abstract: Computed tomography (CT) is pivotal in detecting and monitoring pulmonary
  nodules in lung cancer screening. With the advancement of artificial intelligence
  in medical imaging, accurate lung segmentation has become crucial for reliable feature
  extraction. While traditional methods lack generalizability, deep learning models
  also encounter difficulties including juxtapleural nodules. To overcome the challenge,
  we finetuned a 3D U-Net by randomly masking out 70% of the images, which forces
  the model to infer the missing regions and learn the boundaries of the lungs. Our
  model achieved a Dice of 0.982 in lung segmentation. Notably, our approach achieved
  higher sensitivity compared to three state-of-the-art deep learning models in the
  inclusion of juxtapleural and large masses by 0.11, 0.20, and 0.52, respectively.
  Additionally, it consistently outperformed these models on external datasets. The
  improved result in nodule inclusion allows for more accurate and robust downstream
  analysis and computer-aided diagnosis of lung cancer. Our model also provided pixel-level
  uncertainty estimates, visually presenting where the model is confident or uncertain.
  High-uncertainty areas can be flagged for further examination by both clinicians
  and researchers. Our implementation is available at https://github.com/luotingzhuang/maskedSeg.
tags:
- Accuracy
- Biomedical imaging
- Computational modeling
- Computed tomography
- Computed Tomography
- Deep learning
- Deep Learning
- Image segmentation
- Juxtapleural Nodules
- Lung cancer
- Lung Segmentation
- Lungs
- Masked Encoder
- Reliability
- Uncertainty
- Uncertainty Estimates
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10981085
---
