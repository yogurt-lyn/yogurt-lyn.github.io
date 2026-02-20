---
title: "Method and System for Power Line Detection Based on Maxtree and Graph Signal Processing"
collection: publications
share: false
category: patents
permalink: /publication/patent-power-line
excerpt: 'A novel power line detection framework using Maxtree hierarchical representation combined with graph signal processing to suppress false/miss alarms in UAV aerial images.'
date: 2023-08-25
patent_number: 'CN117011682B'
application_number: 'CN202311079726.4'
grant_date: '2026-01-06'
applicant: 'University of Electronic Science and Technology of China Yangtze Delta Institute (Huzhou)'
inventors: 'Qian, J.; Liu, Y.; Lyu, H.'
status: 'Notice of Grant Received'
abstract: |
  This invention discloses a method and system for power line detection based on Maxtree and graph signal processing. The method includes: acquiring original image data; constructing a color filter based on RGB channel value patterns to retain gray pixels; inputting the original image data into the color filter to obtain a grayscale image; constructing a Maxtree model, setting node attribute signals for the Maxtree model, and segmenting the Maxtree to obtain power line image data by separating power lines from background noise; and obtaining a straight line equation of the power line through graph signal processing. The method utilizes the unique structure of Maxtree combined with graph signal processing to achieve power line detection, and filters out noise based on color differences between power lines and background noise, improving algorithm efficiency and reducing memory consumption. It fundamentally solves false detection issues, thereby reducing power line miss detection.
citation: 'Qian, J.; Liu, Y.; Lyu, H. (2023). Method and System for Power Line Detection Based on Maxtree and Graph Signal Processing. China Invention Patent No. CN117011682B.'
---

## Abstract

This invention discloses a novel power line detection framework using **Maxtree** (a hierarchical image representation) combined with **graph signal processing** for UAV aerial images. The method includes:

1. **Color filtering stage**: Construct a color filter based on RGB channel value patterns to retain gray pixels related to power lines while suppressing background noise.

2. **Maxtree construction**: Build a Maxtree model from the filtered grayscale image, where each node is assigned three attribute components:
   - Gray value
   - Linearity  
   - Length

3. **Graph signal processing**: Perform two-stage filtering on the Maxtree to preserve power line components and suppress background noise, ultimately extracting the straight line equation of power lines.

## Key Innovations

- ✅ **Two-stage filtering** effectively suppresses false alarms while preserving true power lines
- ✅ **Node attribute design** (gray value + linearity + length) enables robust detection under complex backgrounds
- ✅ **Memory efficient**: Maxtree structure reduces computational overhead compared to pixel-wise methods
- ✅ **Field tested**: Applied to low-altitude UAV inspection scenarios with significant reduction in miss detection rate

## Patent Information

| Field | Value |
|-------|-------|
| **Patent Number** | CN117011682B |
| **Application Number** | CN202311079726.4 |
| **Application Date** | 2023-08-25 |
| **Expected Grant Date** | 2026-01-06 |
| **Inventors** | Qian, Jiang; **Liu, Yinan**; Lyu, Haitao |
| **Applicant** | University of Electronic Science and Technology of China Yangtze Delta Institute (Huzhou) |
| **Status** | Notice of Grant Received |
| **IPC Classification** | G06V20/00; G06V10/56; G06N3/0464 |

> 🔗 Official record: [CNIPA Patent Query](https://cpquery.cponline.cnipa.gov.cn/) — CN117011682B
