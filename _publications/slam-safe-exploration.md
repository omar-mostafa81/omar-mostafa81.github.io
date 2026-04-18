---
title: "SLAM-based Safe Indoor Exploration Strategy"
authors: "<strong>O. Mostafa</strong>, N. Evangeliou, A. Tzes"
venue: ICARA 2025
year: 2025
paper_url: "https://ieeexplore.ieee.org/document/YOUR_ID"
tags:
  - SLAM
  - Autonomous Exploration
  - Navigation
  - Mobile Robotics
abstract: >
  We present a safe autonomous exploration strategy for indoor environments, implemented on the Diablo 2-wheeled robot.
  The approach combines SLAM (via RTAB-Map) with a Medial-Axis motion planner that prioritizes robot safety relative
  to obstacles while remaining resilient to sensor noise. Frontier-based exploration drives the robot to unexplored
  regions, generating OctoMaps of complex long indoor environments. The method was validated in real apartment
  environments using fused RGB-D and LiDAR data.
images:
  - src: /assets/images/publications/slam_diablo_robot.png
    caption: "Diablo robot with 3D LiDAR and RealSense D435i"
  - src: /assets/images/publications/slam_octomap.png
    caption: "OctoMap generated from real apartment exploration"
  - src: /assets/images/publications/slam_planner.png
    caption: "Medial-Axis motion planner visualization"
---

This work was conducted at the **Center for AI and Robotics, NYU Abu Dhabi**, under the supervision of Prof. Anthony Tzes.

The robot platform was the Diablo 2-wheeled robot, equipped with a Velodyne 3D LiDAR, Intel RealSense D435i RGB-D camera,
and an Intel NUC i7 onboard computer. Sensor data was fused and validated against a motion capture system.
