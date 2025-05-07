# FusionMedCLIP: A Framework for Few-Shot Medical Anomaly Detection via Adapted Vision-Language Model

**Author:** Ziqian Zhang
**Affiliation:** School of AI and Advanced Computing XI’AN JIAOTONG-LIVERPOOL UNIVERSITY
**Date of Submission/Defense:** April 2025

---

## Abstract

The integration of artificial intelligence into medical imaging holds great promise for improving diagnostic accuracy and efficiency. Among these applications, detecting anomalies in medical images is crucial for timely diagnosis, yet accurately identifying abnormalities with limited labelled data presents a significant challenge due to the inherent rarity of anomalies and the high cost of expert annotation. This necessitates effective few-shot learning approaches. While large Vision-Language Models, such as CLIP, possess strong generalisation capabilities, their direct application to specialised medical domains is hampered by domain shift and the difficulty of crafting effective textual prompts.

To address these issues, this work introduces FusionMedCLIP, a framework designed to efficiently adapt large vision-language models for few-shot medical anomaly detection through synergistic adaptation. The key 4 contributions lie in the synergistic co-optimization of several components: (i) initial medical domain alignment via ROCO pre-training, (ii) automated, knowledge-augmented prompt generation (CoOp+UMLS) replacing manual crafting, (iii) lightweight, parameter-efficient fine-tuning of the visual encoder (ViT) using LoRA and Block Adapters, and (iv) pathology-guided anomaly synthesis to effectively utilize limited training data. This integrated strategy specifically targets the challenges of few-shot learning in clinical settings. Validated on benchmarks including BrainMRI, BUSI, and CheXpert, FusionMedCLIP achieves state-of-the-art few-shot performance, reaching up to 94.8% Image-AUROC on BrainMRI and 89.9% Pixel-AUROC on BUSI (k=16). This significantly surpasses zero-shot CLIP (>37% Image-AUROC gain on BrainMRI) and leading external anomaly detection methods. By synergistically adapting, FusionMedCLIP offers a practical and effective pathway to leverage their power for medical anomaly detection, specifically addressing the dual challenges of domain adaptation and data scarcity in low-resource clinical settings.


## Repository Contents

This repository contains the full PDF version of my [Bachelor of Engineering] dissertation.

*   📄 **`[2144337_ZiqianZhang_FusionMedCLIP A Framework for Few-Shot Medical Anomaly Detection via Adapted Vision-Language Model.pdf]`**: The complete dissertation document.

## How to Access

You can download or view the PDF directly from this repository.

*   To view the PDF: Click on the `[2144337_ZiqianZhang_FusionMedCLIP A Framework for Few-Shot Medical Anomaly Detection via Adapted Vision-Language Model.pdf]` file above.
*   To download: Click on the `[2144337_ZiqianZhang_FusionMedCLIP A Framework for Few-Shot Medical Anomaly Detection via Adapted Vision-Language Model.pdf]` file, then click the "Download" button.

## Contact

For any questions regarding this work, feel free to reach out:
*   Email: `[Ziqian.Zhang21@student.xjtlu.edu.cn]`

---

Thank you for your interest in my research!
