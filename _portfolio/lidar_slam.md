---
title: "[Review] Comparative Study of LiDAR SLAM Algorithms"
excerpt: "Evaluation of LiDAR SLAM algorithms in degraded environments with focus on robustness improvements for dusty conditions. <br/><img src='../images/lidar_slam/main.png'>"
collection: portfolio
order: 9
---

## Introduction

This project evaluates LiDAR-based SLAM (Simultaneous Localization and Mapping) algorithms in environments with reduced visibility, such as dusty mining sites. Dusty conditions introduce noise and occlusions in point cloud data, limiting the effectiveness of traditional SLAM methods. By enhancing algorithm robustness, this research aims to improve autonomous navigation in harsh environments.

<figure style="text-align: center;">
  <img src="../../images/lidar_slam/dusty_environment.png" alt="Dusty Environment" style="max-width: 100%;" />
  <figcaption style="font-style: italic;">Figure 1: Dusty mining environment impacting LiDAR SLAM</figcaption>
</figure>

<figure style="text-align: center;">
  <img src="../../images/lidar_slam/lidar_map.png" alt="LiDAR Map" style="max-width: 100%;" />
  <figcaption style="font-style: italic;">Figure 2: Sample Map generated from LiDAR-based SLAM</figcaption>
</figure>

## Methods

### Filter-Based Methods:
- **FAST-LIO2 with Loop Closure**: Integrates LiDAR-inertial odometry with pose-graph optimization for improved mapping in degraded conditions.

### Graph Optimization-Based Methods:
- **LIO-SAM**: A tightly coupled LiDAR-inertial odometry method using Euclidean-distance loop detection and pose-graph optimization.
- **ART-SLAM**: Modular system integrating ground detection to optimize maps.
- **GLIM**: GPU-accelerated voxelized ICP for enhanced accuracy and efficiency.

Performance metrics include Absolute Trajectory Error (ATE) and mapping quality across datasets, such as the KITTI dataset and dust environment data.

## Results

### Trajectory Results:
<figure style="text-align: center;">
  <img src="../../images/lidar_slam/trajectory_comparison.png" alt="Trajectory Comparison" style="max-width: 100%;" />
  <figcaption style="font-style: italic;">Figure 3: Trajectory comparison across algorithms</figcaption>
</figure>

### Mapping Results:
<figure style="text-align: center; margin: 0;">
  <img src="../../images/lidar_slam/kitti_mapping.png" alt="KITTI Dataset Mapping" style="max-width: 100%;" />
  <figcaption style="font-style: italic; margin-top: 8px;">Figure 4: KITTI Dataset Mapping</figcaption>
</figure>

<figure style="text-align: center; margin: 0;">
  <img src="../../images/lidar_slam/sim_mapping.png" alt="Simulator Dataset Mapping" style="max-width: 100%;" />
  <figcaption style="font-style: italic; margin-top: 8px;">Figure 5: Simulator Dataset Mapping</figcaption>
</figure>

## Discussion

The project is ongoing. Current findings reveal:
- **FAST-LIO2**: Best accuracy in odometry but sensitive to degenerated data.
- **GLIM**: Superior mapping performance with sparse geometric features.

### Future Work:
Developing dust filtering algorithms and integrating them with optimal SLAM methods for evaluation on dusty environment datasets.

## Conclusion

This study highlights the limitations and strengths of different SLAM algorithms under challenging conditions, offering insights for further research and practical implementations in real-world settings.
