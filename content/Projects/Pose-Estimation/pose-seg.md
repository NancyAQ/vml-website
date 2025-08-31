---
title: "From Pose to Semantic Segmentation"
github: "https://github.com/AI-Computer-Vision-BGU/pose2seg"
people: ["David Cohen (PhD Student)", "Dr. Jane Smith"]
description: "Leveraging human pose cues to improve the accuracy and robustness of human semantic segmentation in crowded scenes."
---
### Overview
This sub-project tackles the challenging problem of segmenting humans in densely crowded scenes, where individuals often occlude each other. Traditional segmentation models struggle in these scenarios. We propose a novel multi-task framework that uses estimated human pose as a strong prior to guide the segmentation network, significantly improving performance in complex environments.

### Key Innovations
- **Pose-Guided Attention Modules:** Architectural components that allow the segmentation network to focus on articulated body parts.
- **Synthetic Crowd Generation:** A pipeline for creating realistic synthetic training data for crowded scenarios.
- **Occlusion-Robust Losses:** Novel loss functions designed to handle frequent occlusions.

### Datasets
- COCO-Pose
- CrowdPose
- Our synthetic VML-Crowded dataset (to be released)

### Publications
- D. Cohen, J. Smith, "Pose2Seg: Leveraging Keypoints for Human Instance Segmentation," *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2024. (Submitted)