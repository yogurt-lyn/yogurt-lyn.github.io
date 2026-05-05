---
title: "IP-DFRNet: Implicit Prior Driven Dual-Domain Feature Refinement for Lesion Segmentation in Medical Images"
collection: publications
share: false
category: manuscripts
permalink: /publication/2026-ip-dfrnet-tcsvt
excerpt: 'Position priors before encoding suppress background and guide lesion segmentation; IP-DFRNet combines an Implicit Prior Neural Network (IPNN) with a Dual-domain Feature Refinement (DFR) module for boundary refinement across nine benchmarks.'
date: 2026-05-05
venue: 'IEEE Transactions on Circuits and Systems for Video Technology (under review)'
pages: ''
publisher: 'IEEE'
paperurl: ''
codeurl: ''
citation: 'Yinan Liu, et al. (2026). IP-DFRNet: Implicit Prior Driven Dual-Domain Feature Refinement for Lesion Segmentation in Medical Images. Submitted to IEEE Transactions on Circuits and Systems for Video Technology.'
bibtext: |
  @misc{liu2026ipdfrnet,
    title={IP-DFRNet: Implicit Prior Driven Dual-Domain Feature Refinement for Lesion Segmentation in Medical Images},
    author={Liu, Yinan and others},
    year={2026},
    note={Submitted to IEEE TCSVT}
  }
---

## Abstract

Lesion segmentation in medical images plays a critical role in clinical diagnosis and treatment planning. Despite the significant progress achieved by recent lesion segmentation methods, existing approaches still face two major challenges: (1) complex background interference; (2) boundary ambiguity. To address these challenges, we make the first attempt, to the best of our knowledge, to introduce position priors before the encoding stage. This allows early suppression of background interference and enhancement of lesion regions, while progressively guiding feature extraction throughout the backbone for precise lesion segmentation.

Specifically, we propose an Implicit Prior-driven Dual-domain Feature Refinement Network (IP-DFRNet) that leverages position priors for the early localization of lesion-related regions, followed by the precise refinement of ambiguous boundaries. To suppress background interference, we propose an Implicit Prior Neural Network (IPNN) that leverages SAM-generated masks to modulate input image at the pixel level, enhancing lesion regions while suppressing background. To further enhance fine-grained discriminative ability for lesion boundaries, we design a Dual-domain Feature Refinement (DFR) module, which consists of a Frequency Decoupling Module (FDM) and a Spatial Localization Module (SLM). By progressively refining backbone stage features via spatial-frequency integration, the DFR module precisely separates lesion boundaries from the background. Extensive experiments conducted on 9 medical image segmentation benchmarks demonstrate that IP-DFRNet consistently outperforms state-of-the-art methods in both accuracy and generalization.

## Citation

If you use this work, please cite:

```bibtex
@misc{liu2026ipdfrnet,
  title={IP-DFRNet: Implicit Prior Driven Dual-Domain Feature Refinement for Lesion Segmentation in Medical Images},
  author={Liu, Yinan and others},
  year={2026},
  note={Submitted to IEEE TCSVT}
}
```
