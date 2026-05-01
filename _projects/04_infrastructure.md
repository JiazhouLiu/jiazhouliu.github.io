---
title: 'Fusion of Infrastructure-Based 3D Scene Reconstructions and Mobile Visual-Inertial Odometry for Drift-Resilient Indoor Augmented Reality'
status: ongoing
fundedBy: 'Student Project'
role: 'Project Co-lead'
permalink: /projects/infrastructure/
excerpt: 'This project uses a comparative experimental design to evaluate a baseline smartphone-only AR navigation system against a hybrid system supported by sparse infrastructure cameras. Through a phased approach, first extending the Monash campus app into an AR prototype, then integrating stereo camera-based 3D reconstructions, the study investigates whether periodic infrastructure “checkpoints” can reduce drift and improve robustness in indoor AR navigation under controlled lab conditions.'
teaser: /images/projects/Infrastructure.png
tags:
  - augmented reality
  - infrastructure camera
  - indoor navigation
---

Augmented Reality (AR) is an emerging technology that overlays digital information onto the physical world, allowing users to interact with aligned virtual content through smartphones, head-mounted displays, or other devices. In the context of navigation, AR provides intuitive guidance by embedding directions directly within a user's visual field, thereby reducing reliance on abstract maps and enhancing spatial awareness. In outdoor environments, AR navigation benefits from well-established positioning systems, such as Global Positioning System (GPS). However, extending these capabilities indoors remains challenging, as GPS offers little to no reliable performance for accurate localisation in enclosed environments.

Consequently, the development of indoor AR navigation relies on alternative approaches to localisation, which must address both the absence of GPS and the inherent limitations of smartphone-based localisation. While visual-inertial odometry (VIO) provides device-centred pose estimates, it suffers from drift accumulation and latency, especially in extended indoor use. These issues hinder the reliability of AR navigation apps that depend on accurate, real-time alignment with the physical environment. Recent advances in infrastructure sensing offer opportunities to augment on-device localisation. In particular, fixed cameras capable of reconstructing 3D scenes and aligning them to abstract floor models present a promising pathway for achieving robust, drift-resilient, markerless indoor localisation.

This research aims to examine the current state of research relevant to indoor augmented reality navigation. We plan to evaluate whether fixed infrastructure cameras, fused with device VIO and aligned through a 3D floor model, can support drift-resilient, low-latency indoor AR localisation. Rather than treating infrastructure cameras as primary anchors, the study will test their role as periodic checkpoints to correct drift. The intention is to balance the accessibility of device-only methods with the robustness of infrastructure-supported systems, contributing evidence on how such hybrid designs can enhance the scalability and reliability of markerless indoor AR.

<img src="/images/projects/Infrastructure.png" alt="Using infrastructure for indoor navigation">