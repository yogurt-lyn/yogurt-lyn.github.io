---
title: "Feature Reconfiguration With Visual prior for Medical Lesion Segmentation"
collection: publications
share: false
category: conferences
permalink: /publication/2026-ip-dfrnet-tcsvt
excerpt: 'Position priors before encoding suppress background and guide lesion segmentation; Feature Reconfiguration With Visual prior combines an Implicit Prior Neural Network (IPNN) with a Dual-domain Feature Refinement (DFR) module for boundary refinement across nine benchmarks.'
date: 2026-05-05
venue: 'AAAI 2027 (under review)'
pages: ''
publisher: 'AAAI'
paperurl: 'https://arxiv.org/abs/2609.03535'
codeurl: 'https://github.com/yogurt-lyn/IP-DFRNet'
citation: 'Yinan Liu, et al. (2027). Feature Reconfiguration With Visual prior for Medical Lesion Segmentation. Submitted to AAAI 2027.'
bibtext: |
  @misc{liu2027featurereconfig,
    title={Feature Reconfiguration With Visual prior for Medical Lesion Segmentation},
    author={Liu, Yinan and others},
    year={2027},
    note={Submitted to AAAI 2027}
  }
---

[📄 Paper](https://arxiv.org/abs/2609.03535) · [💻 Code](https://github.com/yogurt-lyn/IP-DFRNet)

## Abstract

Lesion segmentation in medical images plays a critical role in clinical diagnosis and treatment planning. Despite the significant progress achieved by recent lesion segmentation methods, existing approaches still face two major challenges: (1) complex background interference; (2) boundary ambiguity. To address these challenges, we make the first attempt, to the best of our knowledge, to introduce position priors before the encoding stage. This allows early suppression of background interference and enhancement of lesion regions, while progressively guiding feature extraction throughout the backbone for precise lesion segmentation.

Specifically, we propose an Implicit Prior-driven Dual-domain Feature Refinement Network (IP-DFRNet) that leverages position priors for the early localization of lesion-related regions, followed by the precise refinement of ambiguous boundaries. To suppress background interference, we propose an Implicit Prior Neural Network (IPNN) that leverages SAM-generated masks to modulate input image at the pixel level, enhancing lesion regions while suppressing background. To further enhance fine-grained discriminative ability for lesion boundaries, we design a Dual-domain Feature Refinement (DFR) module, which consists of a Frequency Decoupling Module (FDM) and a Spatial Localization Module (SLM). By progressively refining backbone stage features via spatial-frequency integration, the DFR module precisely separates lesion boundaries from the background. Extensive experiments conducted on 9 medical image segmentation benchmarks demonstrate that IP-DFRNet consistently outperforms state-of-the-art methods in both accuracy and generalization.

## Citation

If you use this work, please cite:

```bibtex
@misc{liu2027featurereconfig,
  title={Feature Reconfiguration With Visual prior for Medical Lesion Segmentation},
  author={Liu, Yinan and others},
  year={2027},
  note={Submitted to AAAI 2027}
}
```
