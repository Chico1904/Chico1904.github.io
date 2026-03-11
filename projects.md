---
layout: single
title: "Projects"
permalink: /projects/
---

<br>

---

## HaGIR — Hand Gesture Instructed Robot

*Personal Project*

Initial idea is to be a simple AMR (Autonomous Mobile Robot) equipped with DC motors, encoders, a motor driver and an ESP32. A deep learning model runs with the webcam and sends the predicted label (0–5 fingers) to the ESP32 via MQTT, which then influences the motor control commands.

**Current focus:**
- Hardware (CAD) design
- Finger count detection
- Motor model identification and corresponding control

<figure>
  <img src="/assets/images/cad_hagir.png" alt="HaGIR CAD Design" width="600">
  <figcaption><em>Fig 1. CAD design of the HaGIR robot.</em></figcaption>
</figure>

| | |
|---|---|
| **Tech stack** | PyTorch, C++, Matlab, Fusion360 |
| **Status** | 🔧 Ongoing |
| **Code** | [Finger Count Detection Model](https://github.com/Chico1904/HaGir_CNN) |

---

## Robotics and Autonomous Systems Project Course

*DD2419 — KTH Royal Institute of Technology*

Development of the full software stack for a small robot equipped with several sensors (LIDAR, RGB-D camera, etc.) to perform a 2-step operation:

- **Exploration phase** — mapping the environment, detecting obstacles (to avoid) and objects (to pick up)
- **Collection phase** — using the produced map to collect objects with a robotic arm, placing them in boxes


<figure>
  <video width="560" controls>
    <source src="/assets/videos/dd2419_collection_video.mp4" type="video/mp4">
  </video>
  <figcaption><em>Fig 3. Demo of the collection phase.</em></figcaption>
</figure>

| | |
|---|---|
| **Tech stack** | ROS, Python, C++ |
| **Status** | ✅ Completed |
| **Code** | [Localization Code](https://github.com/Chico1904/ICP-Localization) |

---
