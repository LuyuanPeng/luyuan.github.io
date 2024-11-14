---
title: CHRIIS
summary: Navigation and Vision for Collaborative Human Robot Inspection & Intervention System for Challenging Underwater Environments 
date: 2024-11-02
# external_link: https://github.com/pandas-dev/pandas
tags:
  - Marine Robotics
  - Model-based Image Compression
  - Virtual Tethering
image: 
  caption: "Team members in CHRIIS"
--- 

This project focuses on developing AI/ML-based computer vision solutions to address real-time video transmission challenges in underwater robotics, specifically for tetherless control of remotely operated vehicles (ROVs). To enable operators to monitor and manipulate the underwater environment in real-time, my work explores advanced data compression techniques designed to overcome the low data rates typically encountered in underwater communication, where acoustic modems offer limited bandwidth and optical modems face range constraints. 

To address these limitations, we leverage a combination of machine learning and computer vision techniques. Our approach begins with creating a comprehensive 3D model of the environment during an initial inspection run. This model serves as a reference for subsequent inspections, allowing for an efficient transmission strategy: only the difference between the expected view and the live camera feed is transmitted. The result is a sparse, highly compressible difference image that significantly reduces data size. 

This research includes developing a novel view synthesis (NVS) model trained on data from the initial inspection, alongside a CNN-based camera pose estimation model, implemented and trained using PyTorch. The pose estimation model predicts the camera’s position for new views, while the NVS model generates an expected image based on that pose. This expected image is compared to the live feed, and only the differential information is transmitted, making real-time video feasible within the limited bandwidth of underwater communication channels. Our work aims to enhance the operational capabilities of ROVs, enabling faster, efficient, and high-quality visual data transmission for underwater inspection and exploration applications. 

This approach has been deployed on real ROV systems and successfully tested in open waters, demonstrating its practical viability in challenging underwater environments.


<!--more-->
