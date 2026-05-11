---
title: 'A Context-Aware Computing Framework for Performance Improvement in Distributed Vision-Based Augmented Reality'
status: Ongoing
fundedBy: 'Student Project'
role: 'Project Lead'
permalink: /projects/contextAware/
excerpt: 'This project aims to address the limitations identified in the current state of the art by designing and evaluating a context-aware computing framework for distributed vision-based AR systems.'
teaser: /images/projects/time_breakdown.png
tags:
  - augmented reality
  - context-aware
  - artificial intelligence
---
This project aims to design and implement a context-aware Augmented Reality (AR) system running on the Apple Vision Pro (AVP). The system focuses on a vision-based task that is object detection. Since this task is computationally intensive, the system adopts a distributed architecture where the AVP captures visual input and offloads heavy inference tasks to a remote server.

However, distributed AR systems must deal with changing network conditions and limited device resources such as battery. Poor bandwidth or high delay can increase transmission time, while limited battery life restricts how frequently the system can monitor the environment. Therefore, fixed system settings may not work well across different runtime conditions, which introduces to the use of context-aware adaptation.

The core of this project is an adaptation mechanism that uses network bandwidth, network delay, and battery level as contextual attributes. Image resolution is adjusted according to network conditions to reduce transmission overhead and latency, while the network probing interval is controlled by both network status and battery level to balance context freshness and monitoring cost. Compared with fixed-parameter approaches, the proposed system aims to achieve a better trade-off among latency, accuracy, and energy consumption in distributed vision-based AR scenarios.

<img src="/images/projects/time_breakdown.png" alt="Context Aware Computing">

<img src="/images/projects/CAmodule_breakdown.png" alt="Context Aware Computing">