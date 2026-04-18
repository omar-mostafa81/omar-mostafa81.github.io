---
title: "Unified Teleoperation Pipeline"
subtitle: "Data Collection for Multiple Robot Embodiments · Turing Robotics"
short_desc: "A unified teleoperation framework supporting VR, leader arm, and keyboard inputs across multiple robot platforms."
order: 3
icon: "🕹️"
thumb: /assets/images/projects/teleop_thumb.jpg
tags:
  - Teleoperation
  - ROS 2
  - Isaac Lab
  - Data Collection
images:
  - src: /assets/images/projects/teleop_diagram.jpg
    caption: "Unified teleoperation pipeline architecture"
  - src: /assets/images/projects/teleop_demo.jpg
    caption: "VR-based teleoperation demo"
---

A unified teleoperation framework developed at **Turing Robotics** that supports multiple input sources and robot
embodiments for scalable robot learning data collection.

**Input sources:** VR/Quest 3, Leader Arm, Keyboard

**Supported robots:** Unitree G1, Franka Research 3, Dobot X-Trainer, Isaac Lab (simulation)

**Architecture:** The Unified Teleop Core normalizes inputs to SE3 poses, passes them through a safety + Pinocchio IK
controller, and routes commands to Real or Sim drivers. Data is recorded and saved to HDF5.
