---
layout: page
title: Swin UNETR for Brain Tumor Segmentation
description: Explainable Transformer-based 3D segmentation of brain tumors in multi-contrast MRI (BraTS).
img:
importance: 1
category: research
---

**Role:** Author and lead researcher (undergraduate thesis, Universidad de Valparaíso, 2024).

This project introduced a **Swin UNETR**-based pipeline for 3D semantic segmentation of brain tumors in multi-contrast magnetic resonance imaging. The model achieves a **Dice score of 0.89 on the BraTS dataset**, while leveraging its attentional nature to deliver visually understandable interpretability via intermediate-layer extraction and **Grad-CAM**.

The motivation was clinical: despite remarkable AI progress, real-world adoption remains limited due to opacity of data-driven decisions. By providing intuitive, layer-level visual explanations alongside accurate segmentation, the pipeline aims to **enhance trust and clinical acceptance** of AI tools in radiology workflows.

**Key contributions**

- Adaptation of Swin UNETR for 3D multi-contrast MRI segmentation.
- Attention-based interpretability extraction.
- Quantitative benchmarking on BraTS.
- Foundation for the broader research line on quantitative XAI evaluation pursued in my MSc and PhD.
