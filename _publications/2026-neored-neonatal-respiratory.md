---
title: "NeoRed: A Knowledge-Logic-Alignment Multimodal Large Language Model for Neonatal Respiratory Disease Diagnosis"
collection: publications
share: false
category: conferences
permalink: /publication/2026-neored-neonatal-respiratory
excerpt: 'The first MLLM tailored for neonatal respiratory disease diagnosis: NeoRed jointly models chest X-rays with clinical context under a Knowledge–Logic–Alignment (KLG) framework, with datasets NeoCXR and NeoCXR-EV.'
date: 2026-05-05
venue: 'AAAI 2027 (under review)'
pages: ''
publisher: 'AAAI'
paperurl: 'https://arxiv.org/abs/2609.03527'
codeurl: 'https://github.com/yogurt-lyn/NeoRed'
citation: 'Yinan Liu, et al. (2027). NeoRed: A Knowledge-Logic-Alignment Multimodal Large Language Model for Neonatal Respiratory Disease Diagnosis. Submitted to AAAI 2027.'
bibtext: |
  @misc{liu2027neored,
    title={NeoRed: A Knowledge-Logic-Alignment Multimodal Large Language Model for Neonatal Respiratory Disease Diagnosis},
    author={Liu, Yinan and others},
    year={2027},
    note={Submitted to AAAI 2027}
  }
---

[📄 Paper](https://arxiv.org/abs/2609.03527) · [💻 Code](https://github.com/yogurt-lyn/NeoRed)

## Abstract

Neonatal respiratory diseases are a leading cause of neonatal morbidity and mortality, posing significant challenges in clinical practice. While Multimodal Large Language Models (MLLMs) have demonstrated strong capability in vision–language understanding and automated report generation, those trained on adult data suffer from domain gaps and struggle to effectively leverage multidimensional clinical context, limiting their reliability for neonatal diagnosis.

To address these challenges, we propose NeoRed, to the best of our knowledge, the first MLLM tailored for neonatal respiratory disease diagnosis. Specifically, NeoRed jointly models X-rays with clinical context (developmental factors, perinatal risks, and physiological status) to generate structured reports comprising imaging conclusion and disease diagnosis. To mirror neonatologist diagnostic logic and further enhance multimodal joint diagnosis, we introduce a novel Knowledge–Logic–Alignment (KLG) framework with three modules: (1) **Knowledge Prior Injection (KPI)** for injecting neonatologist-derived priors into multimodal representations at the input stage, implicitly guiding disease-specific attention across modalities; (2) at the output stage, **Diagnostic Logic Constraint (DLC)** to align global semantics of the generated report with multimodal diagnostic logic; and (3) **Visual Semantic Grounding (VSG)** to establish semantic correspondence between visual features and imaging conclusion.

To support training and evaluation, we construct NeoCXR and NeoCXR External Validation (NeoCXR-EV), two multimodal neonatal report generation datasets curated from real-world clinical workflows. NeoRed achieves ROUGE-L of 53.29% and Clinical Efficacy F1 of 65.19% on NeoCXR, and maintains robust performance on NeoCXR-EV, outperforming existing MLLMs. It also achieves competitive results on adult benchmarks (MIMIC-CXR, IU-Xray), highlighting strong cross-population generalization.

## Citation

If you use this work, please cite:

```bibtex
@misc{liu2027neored,
  title={NeoRed: A Knowledge-Logic-Alignment Multimodal Large Language Model for Neonatal Respiratory Disease Diagnosis},
  author={Liu, Yinan and others},
  year={2027},
  note={Submitted to AAAI 2027}
}
```
