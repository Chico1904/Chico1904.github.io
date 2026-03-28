---
layout: single
title: "Research"
permalink: /research/
---

## ALARS Research Project ([Project Page](https://www.digitalfutures.kth.se/project/alars-aerial-launch-and-recovery-system-for-autonomous-underwater-vehicles/))

### Overview
The ALARS (Aerial Launch and Recovery System for Autonomous Underwater Vehicles) project investigates a drone-based solution for autonomous AUV recovery in maritime environments. Traditional methods rely on large vessels and manual handling, which are costly and risk-prone.

### Key Contributions
- Designed and evaluated search planning strategies for efficient AUV localization  
- Developed a hybrid YOLO–Canny pipeline for AUV detection and orientation estimation  
- Validated performance in real-world field tests  

### Search Planning
Explored alternative search planning algorithms to improve efficiency and robustness over non-informative strategies (e.g., spiral)

[Project Report](/assets/rp_report.pdf)

### AUV Detection
Developed a hybrid detection pipeline combining YOLO for buoy detection with Canny edge detection for AUV head localization and orientation estimation. This enables reliable alignment during recovery, accounting for the cable-connected buoy.

<figure>
  <video width="560" controls>
    <source src="/assets/videos/rp_demo1.mp4" type="video/mp4">
  </video>
  <figcaption><em>YOLO–Canny detection pipeline during field testing.</em></figcaption>
</figure>