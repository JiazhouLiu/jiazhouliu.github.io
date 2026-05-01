---
title: 'AI-facilitated Brain Tumour Segmentation in Immersive Environments'
status: ongoing
fundedBy: 'Monash FIT Seed Grant 2024'
role: 'Project Lead'
permalink: /projects/brainTumourSeg/
excerpt: 'This project develops an AI-driven system to automate brain tumour segmentation from complex 3D MRI scans, reducing the need for time-consuming and error-prone manual annotation by medical experts. It combines deep learning models with immersive visualisation (e.g., AR/VR), allowing clinicians to interact with and refine tumour predictions directly in 3D space.'
teaser: /images/projects/AI-facilitated-Brain-Tumour-Segmentation.jpg
tags:
  - digital health
  - virtual reality
  - artificial intelligence
---

<img src="/images/publications/teaser_brainTumour.png" alt="Brain Tumour Segmentation Tool">

Due to their complex and heterogeneous nature, brain tumours pose significant challenges in diagnosis and treatment. Traditional methods for tumour segmentation in medical imaging, particularly Magnetic Resonance Imaging (MRI), often require manual intervention for interpreting medical scans, such as medical experts manually annotating scans by marking areas of interest like tumours or lesions.

Unlike natural images, most medical scans come as a volume or, in other words, as a 3D image. These volumes come with 200 to 300 slices, and all these slices need to be annotated by medical experts to come up with a diagnosis. This method, though valuable, is subjective, time-consuming, and occasionally prone to errors. This means that people might experience delays in getting diagnosed or may not have access to the best treatments.

We propose to streamline this tedious manual process by introducing a deep learning-based approach for automated brain tumour segmentation inspired by recent Vision Foundational Models (VFM) such as the Segment Anything Model (SAM). The output data from this approach will then be processed by an advanced visualisation engine and displayed via immersive technologies, such as Augmented Reality (AR). Our system allows natural interactions (e.g., hand gestures) with 3D data spaces of tumour regions predicted by the proposed deep learning model.

The proposed approach comprises two components, namely, a deep learning model implementation and a visualisation component. Deep learning model implementation involves training state-of-the-art deep learning models on large-scale MRI datasets annotated by expert radiologists. These models will be designed to accurately segment various tumour classes, including enhanced tumour, non-enhancing tumour, and edema regions. We will leverage advanced deep learning architectures and techniques such as convolutional neural networks (CNNs), attention mechanisms, and transfer learning to enhance the segmentation accuracy and robustness of the proposed deep learning model.

<img src="/images/publications/AI-facilitated-Brain-Tumour-3.png" alt="Brain Tumour Segmentation Tool Screenshots">

Recent studies have shown the potential use of Augmented Reality (AR) to display 3D visualisations in the medical field. Inspired by those works, we will develop an innovative pipeline for 3D visualisation of segmented tumour regions alongside the original MRI scans. This will enable clinicians to analyse tumour characteristics comprehensively and interact with 3D volume data naturally, leading to more informed decision-making in diagnosis and treatment planning.

## Pulications
Pooryousef, V., Peiris, H., Liang, H., Li, A., Chen, Z., Dwyer, T. and **Liu, J.**, (2025 Oct), SAMMed-VR: Integrated Segment Anything Model in Virtual Reality for Supervised Brain Tumour Segmentation. [Publication Link](/publication/sammedvr)

## Protoype Video
[Video Link](https://youtu.be/bNXE739Gef0){: target="_blank"}