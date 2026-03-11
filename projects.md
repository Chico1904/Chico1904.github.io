---
layout: single
title: "Projects"
permalink: /projects/
---
---
## HaGIR - Hand Gesture Instructed Robot (Personal Project)

**Description:** Initial idea is to be a simple AMR (Autonomous Mobile Robot) equipped with DC motors, encoders, a motor driver and an ESP32. A deep learning model runs with the webcam and sends the predicted label (0-5 fingers) to the esp32 via MQTT, which thens influences the motor controls commands. Initial focus of this project lies on:
- Hardware (CAD) design
- Finger count detection
- Motor model identification and corresponding control

<!-- IMAGE: replace the src with your image path, e.g. /assets/images/project1.jpg  ![Project 1 Screenshot](/assets/images/project1-placeholder.png) -->


**Tech stack:** PyTorch, C++, Matlab, Fusion360
**Status:** Ongoing
Check the GitHub repo of the [finger count detection model]([https://github.com/Chico1904/ICP-Localization](https://github.com/Chico1904/HaGir_CNN))
  
## Robotics and Autonomous Systems Project Course (DD2419 KTH course)

**Description:** The projected consisted of developing the software for an small robot equiped with several sensors (LIDAR, RGB-D camera, etc) to perform a 2-step operation: 
- An exploration phase, consisting of mapping the environment, including obstacles (to avoid) and objects (to pick later on)
- A collection phase, in which the robot would used the produced environment map to collect the objects with a robotic arm, placing them on boxes.

<!-- IMAGE: replace the src with your image path, e.g. /assets/images/project1.jpg  ![Project 1 Screenshot](/assets/images/project1-placeholder.png) -->


<!-- VIDEO (local file): place your .mp4 in /assets/videos/ and update the src -->
<video width="560" controls>
  <source src="/assets/videos/dd2419_collection_video.mp4" type="video/mp4">
</video>


- **Tech stack:** ROS, Python, C++
- **Status:** Completed
- [Localization code](https://github.com/Chico1904/ICP-Localization)

---
