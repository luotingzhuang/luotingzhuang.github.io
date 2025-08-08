---
title: 'DART: Deformable Anatomy-Aware Registration Toolkit for Lung CT Registration
  with Keypoints Supervision'
authors:
- Yunzheng Zhu
- Luoting Zhuang
- Yannan Lin
- Tengyue Zhang
- Hossein Tabatabaei
- Denise R Aberle
- Ashley E Prosper
- Aichi Chien
- William Hsu
date: '2024-05-01'
publishDate: '2025-08-08T01:08:53.802496Z'
publication_types:
- paper-conference
publication: '*2024 IEEE International Symposium on Biomedical Imaging (ISBI)*'
doi: 10.1109/ISBI56570.2024.10635326
abstract: Spatially aligning two computed tomography (CT) scans of the lung using
  automated image registration techniques is a challenging task due to the deformable
  nature of the lung. However, existing deep-learning-based lung CT registration models
  are not trained with explicit anatomical knowledge. We propose the deformable anatomy-aware
  registration toolkit (DART), a masked autoencoder (MAE)-based approach, to improve
  the keypoint-supervised registration of lung CTs. Our method incorporates features
  from multiple decoders of networks trained to segment anatomical structures, including
  the lung, ribs, vertebrae, lobes, vessels, and airways, to ensure that the MAE learns
  relevant features corresponding to the anatomy of the lung. The pretrained weights
  of the transformer encoder and patch embeddings are then used as the initialization
  for the training of downstream registration. We compare DART to existing state-of-the-art
  registration models. Our experiments show that DART outperforms the baseline models
  (Voxelmorph, ViT-V-Net, and MAE-TransRNet) in terms of target registration error
  of both corrField-generated keypoints with 17%, 13%, and 9% relative improvement,
  respectively, and bounding box centers of nodules with 27%, 10%, and 4% relative
  improvement, respectively. Our implementation is available at https://github.com/yunzhengzhu/DART.
tags:
- Anatomy-Aware Pretraining
- Brain modeling
- Computational modeling
- Computed tomography
- Image registration
- Lung
- Lung image registration
- Masked Autoencoder
- Training
- Transformers
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10635326
---
