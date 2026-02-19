---
title: "Power Line Detection Based on Maxtree and Graph Signal Processing"
collection: publications
category: manuscripts
permalink: /publication/2023-igarss-power-line
excerpt: 'A power line detection method based on Maxtree for UAV aerial images, using graph signal processing framework with two-stage filtering.'
date: 2023-07-16
venue: 'IGARSS 2023 - IEEE International Geoscience and Remote Sensing Symposium'
pages: '6182-6185'
publisher: 'IEEE'
paperurl: 'https://ieeexplore.ieee.org/document/10282535'
codeurl: ''
citation: 'Yinan Liu, Jiang Qian, Junzheng Jiang, Haitao Lyu, Yong Wang. (2023). Power Line Detection Based on Maxtree and Graph Signal Processing. <i>IGARSS 2023</i>, 6182-6185.'
bibtext: |
  @inproceedings{liu2023power,
    title={Power Line Detection Based on Maxtree and Graph Signal Processing},
    author={Liu, Yinan and Qian, Jiang and Jiang, Junzheng and Lyu, Haitao and Wang, Yong},
    booktitle={IGARSS 2023 - IEEE International Geoscience and Remote Sensing Symposium},
    pages={6182--6185},
    year={2023},
    organization={IEEE}
  }
---

## Abstract

Low-altitude unmanned aerial vehicle (UAV) remote sensing facilitates the frequent detection of power lines and liberates manual inspection. In the process of UAV power line inspection, power line detection in UAV aerial images plays an important role. But false alarms and miss alarms often occur during the detection process. 

Aiming at this problem, a power line detection method based on Maxtree is proposed. This method transforms the UAV aerial images into a graph structure, i.e., Maxtree, and detects the power lines under graph signal processing frame. Two-stage filtering is designed to preserve power line components:

1. **Preprocessing stage**: Filters out most of the background part according to the color value
2. **Maxtree filtering stage**: Performs filtering on the Maxtree created with connectivity and gray value

For each node, three attribute components are assigned to facilitate detection:
- Gray value
- Linearity  
- Length

## Citation

If you use this work, please cite:

```bibtex
@inproceedings{liu2023power,
  title={Power Line Detection Based on Maxtree and Graph Signal Processing},
  author={Liu, Yinan and Qian, Jiang and Jiang, Junzheng and Lyu, Haitao and Wang, Yong},
  booktitle={IGARSS 2023 - IEEE International Geoscience and Remote Sensing Symposium},
  pages={6182--6185},
  year={2023},
  organization={IEEE}
}

