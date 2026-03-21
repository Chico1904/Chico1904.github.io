---
layout: single
title: "Projects"
permalink: /projects/
classes: wide
---

## HaGIR — Hand Gesture Instructed Robot

**Personal Project**

Autonomous Mobile Robot (AMR) controlled via hand gestures. A vision model detects finger count (0–5) from a webcam stream and sends commands to an ESP32 via MQTT, which drives motor control.

**Current focus**
- Hardware design (CAD)
- Finger count detection (vision model)
- Motor modeling and control

<figure>
  <img src="/assets/images/cad_hagir.png" alt="HaGIR CAD Design" width="420">
  <figcaption><em>CAD design of the HaGIR robot.</em></figcaption>
</figure>

**Tech**: PyTorch · C++ · MATLAB · Fusion 360  
**Status**: 🔧 Ongoing  
**Code**: [Finger Count Detection Model](https://github.com/Chico1904/HaGir_CNN)

---

## Robotics and Autonomous Systems Project

**KTH — DD2419**

Full software stack for an autonomous robot using LIDAR and RGB-D sensing. The system performs:

- **Exploration**: mapping, obstacle avoidance, object detection  
- **Collection**: object retrieval using a robotic arm based on the generated map  

<figure>
  <video width="560" controls>
    <source src="/assets/videos/dd2419_collection_video.mp4" type="video/mp4">
  </video>
  <figcaption><em>Collection phase demonstration.</em></figcaption>
</figure>

**Tech**: ROS · Python · C++  
**Status**: ✅ Completed  
**Code**: [Localization (ICP)](https://github.com/Chico1904/ICP-Localization)