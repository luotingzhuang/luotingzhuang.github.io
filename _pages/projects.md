---
title: "Projects"
permalink: /projects/
layout: single
author_profile: true
classes: wide
---

## Generative AI for Cross-Trial Translation

*Bristol Myers Squibb · Summer 2026*

Developed a generative modeling framework to support cross-study translation among clinical-trial datasets with limited feature overlap, enabling more consistent analysis across heterogeneous studies.

- Engineered a multimodal variational autoencoder to represent trial-specific features in a shared latent space.
- Aligned data from three clinical trials despite differences in feature availability and study design.
- Analyzed the learned representations to identify candidate biomarkers associated with clinical outcomes.

## Explainable Vision–Language Modeling for Lung Cancer Prediction

*Journal of Biomedical Informatics · 2025*

Developed a vision–language model that learns clinically meaningful imaging biomarkers by aligning lung-nodule CT images with radiologist-defined semantic descriptions. The project was designed to improve both the generalizability and interpretability of lung cancer prediction across diverse clinical settings.

- Fine-tuned CLIP with parameter-efficient learning to align multi-view CT images and semantic text features.
- Evaluated the model across the National Lung Screening Trial and four external datasets; it achieved an AUROC of 0.901 and AUPRC of 0.776 on the NLST test set.
- Enabled zero-shot prediction of interpretable characteristics such as nodule margin, consistency, and pleural attachment.

[Paper](https://www.sciencedirect.com/science/article/pii/S1532046425001765) · [Code](https://github.com/luotingzhuang/CLIP_nodule)

## Modeling Lung Nodule Progression with Pseudotime

*Medical Imaging with Deep Learning · 2026*

Adapted pseudotime inference from single-cell biology to reconstruct lung-nodule progression trajectories from cross-sectional CT images, addressing the limited availability of longitudinal imaging data.

- Modeled 13,626 nodule snapshots from two lung-screening cohorts using diffusion pseudotime and a deep learning framework combining a variational autoencoder with a neural ordinary differential equation.
- Validated the learned trajectories against a held-out longitudinal test set and clinically meaningful imaging characteristics.
- Demonstrated that pseudotime and changes in pseudotime stratify malignancy risk and provide predictive information beyond established semantic biomarkers.

[Paper](https://proceedings.mlr.press/v315/zhuang26a.html) · [Code](https://github.com/luotingzhuang/Pseudotime4Nodules)

## Multimodal AI for Cancer Outcome Prediction

*SPIE Medical Imaging: Digital and Computational Pathology · 2022*

Built a weakly supervised deep learning framework that integrates medical imaging and genomic data to predict patient outcomes across multiple cancer types. The approach uses survival outcomes as its only label, reducing its dependence on labor-intensive expert annotations and feature engineering.

- Integrated histopathology, radiology, and genomics without requiring manual image annotations, tumor segmentation, or handcrafted features.
- Evaluated the framework in glioma and non-small cell lung cancer and validated its robustness on two external cohorts from Germany and the United States.
- Applied interpretability methods to identify prognostic features associated with favorable and poor outcomes across modalities.

[Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12039/120390Z/Deep-learning-based-integration-of-histology-radiology-and-genomics-for/10.1117/12.2626318.full) · [Code](https://github.com/MultimodalFusion/multimodalfusion)
