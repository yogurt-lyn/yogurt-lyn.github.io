---
title: "From Infusion to Assimilation Distillation for Medical Image Segmentation"
collection: publications
share: false
category: conferences
permalink: /publication/2026-cvpr-iad-medical-segmentation
excerpt: 'IAD distills foundation models (e.g. SAM) into lightweight segmenters via Knowledge Infusion Stage (KIS) and Knowledge Assimilation Stage (KAS), improving Dice and cross-dataset generalization.'
date: 2026-06-10
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2026'
pages: ''
publisher: 'IEEE'
paperurl: 'https://cvpr.thecvf.com/virtual/2026/poster/36239'
codeurl: 'https://github.com/hjklearn/IAD'
citation: 'Jiankang Hong, Yinan Liu, et al. (2026). From Infusion to Assimilation Distillation for Medical Image Segmentation. In <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</i>.'
bibtext: |
  @inproceedings{hong2026iad,
    title={From Infusion to Assimilation Distillation for Medical Image Segmentation},
    author={Hong, Jiankang and Liu, Yinan and others},
    booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2026}
  }
---

## Abstract

Although foundation models (e.g. SAM) perform remarkably in medical image segmentation, their high computational complexity limits deployment. Knowledge distillation (KD) allows lightweight models to inherit the representational capabilities of large models, thereby mitigating this issue. Existing KD methods enhance student performance, but due to teacher–student different feature advantages, they neglect to internalize and integrate the student’s semantic information adaptively after knowledge transfer, causing poor knowledge assimilation and limiting gains and generalization.

To address this limitation, we propose a novel medical image segmentation framework, **from infusion to assimilation distillation (IAD)**. In **Knowledge Infusion Stage (KIS)**, to semantically align teacher–student prediction distributions, soft-label distillation is combined with a class-weighted prototype alignment strategy. In **Knowledge Assimilation Stage (KAS)**, to promote adaptive semantic assimilation, a contrastive semantic self-optimization strategy refines student predictions through positive and negative sample pairs and imposes reverse constraints on encoder features to enhance semantic consistency. IAD achieves Dice gains of 4.32% on Synapse, 1.85% on ACDC, and 2.42% on Polyp datasets, and delivers an average 4.16% generalization gain on ISIC2018, PH2, BUSI, and STU datasets, outperforming mainstream KD methods.

## Citation

If you use this work, please cite:

```bibtex
@inproceedings{hong2026iad,
  title={From Infusion to Assimilation Distillation for Medical Image Segmentation},
  author={Hong, Jiankang and Liu, Yinan and others},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
```
