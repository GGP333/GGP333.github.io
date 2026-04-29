---
layout: about
title: About
permalink: /
subtitle: PhD Student · <a href='https://postgrados.uv.cl/doctorado/ingenieria-salud'>Doctorado en Ciencias e Ingeniería para la Salud</a>, <a href='https://www.uv.cl/'>Universidad de Valparaíso</a> · Researcher at <a href='https://i-health.cl/'>Millennium Institute iHEALTH</a>.

profile:
  align: right
  image: prof_pic.png
  image_circular: true # crops the image to make it circular
  more_info: >
    <p><strong>Gabriel Guerra Pinto</strong></p>
    <p>School of Biomedical Engineering</p>
    <p>Universidad de Valparaíso</p>
    <p>Reñaca, Valparaíso, Chile</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a PhD student in the [Doctorado en Ciencias e Ingeniería para la Salud](https://postgrados.uv.cl/doctorado/ingenieria-salud) at [Universidad de Valparaíso](https://www.uv.cl/) (Chile), and a researcher at the [Millennium Institute for Intelligent Healthcare Engineering (iHEALTH)](https://i-health.cl/). My work sits at the intersection of **deep learning, explainable AI, and medical imaging**.

My focus is on building **AI solutions with the potential for large, real-world impact in healthcare** — particularly in radiology and oncology — by designing systems that are explainable, trustworthy, and clinically usable. My doctoral research develops an **explainable, neuro-fuzzy vision–language framework** for oncology that fuses multi-contrast MRI with unstructured clinical text and produces traceable descriptors aligned with radiology lexicons such as BI-RADS and PI-RADS. Methodologically, I combine **self-supervised vision encoders** (UNETR / Swin-UNETR with MAE or SimCLR), **contrastive vision–language fusion**, and **neuro-fuzzy inference modules** (NFIS / ANFIS) that explicitly model uncertainty and emit interpretable if–then rules. The long-term goal is transferable, explainable diagnostic support that strengthens clinical decision-making in resource-limited regional hospitals, beyond the Metropolitan Region of Chile.

I lead and contribute to several translational AI projects within iHEALTH:

- **Brain tumor MRI segmentation** (FONDECYT 1221938 / iHEALTH): evaluation of state-of-the-art 3D architectures (Attention U-Net 3D and Swin-UNETR) and design of novel **quantitative metrics for visual explainability** (Grad-CAM, feature extraction) ensuring the anatomical coherence of generated explanations.
- [**mamAI-Dens**](https://i-health.cl/) (FONDEF IT23I0040): preprocessing pipelines and U-Net / nnU-Net models for **fibroglandular tissue segmentation in mammography**, plus an integrated multi-task model for ACR (BI-RADS) classification using multi-task regularization to align segmentation and diagnostic outputs.
- **VIZCACHA** (VIU25P0233 — *Visualization in Cancer with Assisted Chat*): conversational radiology platform built on **LLMs + RAG**, with a companion module **VIZCACHA-PDF** for medical OCR / clinical NLP developed with the [Speaknosis](https://i-health.cl/) startup.
- Translational work at *Hospital Carlos Van Buren*: **DICOM anonymization** pipelines for the mamAI-Dens database and **neuroradiology support GUIs** integrated with the hospital workflow.

I hold a degree in **Biomedical Engineering** (*Ingeniería Civil Biomédica*, Universidad de Valparaíso, 2024) and I am finishing my **MSc in Engineering Sciences, Biomedical Engineering** (2026). Beyond research, I have served as teaching assistant in *Gestión de Datos en Salud* and *Taller de Integración Perfil de Egreso*, lectured the *AI and Applications in Health* workshop at the iHEALTH Summer School, and presented my work at the *Jornada de Jóvenes Investigadores* (Uruguay), the *International Conference on Image and Signal Processing* (Colombia), the *COPEC-UC AI Seminar*, and the *UDP Data Science Congress*.

I am always open to collaborations on **explainable medical AI**, clinical deployment of foundation models, and translational radiology tools. Feel free to reach me by [email](mailto:gabriel.guerrap99@gmail.com).
