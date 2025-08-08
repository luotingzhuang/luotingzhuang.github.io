---
title: Comparing the characteristics and robustness of imaging features via prompt
  selection in generalist segmentation models
authors:
- Luoting Zhuang
- Seyed Mohammad Hossein Tabatabaei
- Denise R. Aberle
- Ashley E. Prosper
- William Hsu
date: '2025-04-01'
publishDate: '2025-08-08T01:08:53.778960Z'
publication_types:
- paper-conference
publication: '*Medical Imaging 2025: Imaging Informatics*'
doi: 10.1117/12.3049090
abstract: 'Machine learning models have been developed on computed tomography (CT)
  scans to advance lung cancer diagnosis and prognosis. While various types of features
  are extracted from CT scans, the nature and robustness of these features are still
  not well understood. These imaging features are challenging to interpret as the
  information they capture is often unclear. Here, we aim to investigate different
  imaging features by employing a novel method: selecting prompts based on feature
  similarity for nodule segmentation. We utilize two generalist foundation models,
  SegGPT and SAM2, which leverage in-context information from a pair of prompt images
  and segmentation guides. This approach enables the models to execute an out-of-domain
  segmentation task effectively. However, their effectiveness depends on the prompt
  example, performing better when prompt and test images share similar semantics,
  backgrounds, and appearances. We used four features for prompt selection: pixel
  intensity, radiomics features, imaging biomarker foundation features, and fine-tuned
  Contrastive Language-Image Pre-Training (CLIP) features. Among the features examined,
  CLIP features-based prompt selection shows superior segmentation accuracy and robustness
  on external datasets by focusing more effectively on nodule characteristics. The
  combination of foundation and CLIP features provides complementary benefits and
  enhances segmentation performance: foundation features effectively identify prompts
  with similar backgrounds, while CLIP features excel at finding prompts with similar
  nodule characteristics. Our findings provide valuable insights into commonly used
  imaging features, helping researchers select the most appropriate features for specific
  prediction tasks.'
links:
- name: URL
  url: 
    https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13411/134110Z/Comparing-the-characteristics-and-robustness-of-imaging-features-via-prompt/10.1117/12.3049090.full
---
