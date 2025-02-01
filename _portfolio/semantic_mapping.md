---
title: "Semantic Mapping with a Legged Robot"
excerpt: "Leveraging the mobility and sensor field-of-view of a legged robot to perform semantic mapping in industry office environments. <br/><img src='../images/semantic_mapping/industrial_setting.png'>"
collection: portfolio
order: 4
---

## Introduction

Traditional exploration in robotics has primarily aimed at maximizing the discovery of free space quickly. However, many real-world applications, such as industrial layout tracking and construction site inspection, require detailed, object-level maps enriched with semantic information. 

This project leverages the unique mobility and large sensor field-of-view of a legged robot to perform semantic mapping in complex environments, providing rich contextual understanding that enhances operational efficiency. By enabling accurate object detection and reconstruction, the proposed approach addresses challenges in cluttered environments, improving decision-making in critical fields like infrastructure inspection and industry management.

<figure style="text-align: center;">
  <img src="../../images/semantic_mapping/semantic_map_illustration.png" alt="Legged Robot Semantic Mapping" style="max-width: 100%; margin: 0 auto;" />
  <figcaption style="font-style: italic;">Figure 1: Semantic Mapping in Action</figcaption>
</figure>


## Method

This project fuses data from **SpotCAM** (a 360 panoramic camera) and an **OS1 LiDAR** to develop a semantic mapping system tailored for a legged robot to explore and map unknown environments. The system integrates advanced object detection and reconstruction techniques, focusing on building object-level dense cloud maps that provide semantic understanding of the environment.
<figure style="text-align: center;">
  <img src="../../images/semantic_mapping/hardware_platform.png" alt="Hardware Platform" style="max-width: 100%; margin: 0 auto;" />
  <figcaption style="font-style: italic;">Figure 2: Hardware Platform</figcaption>
</figure>

### Key Features:
- **Sensor Fusion**: Combines LiDAR and camera data for precise object detection and mapping.
- **Dense Cloud Generation**: Creates detailed point cloud representations enriched with object-level semantics.
- **Robustness**: Avoids regions with inconsistent sensor measurements and captures target objects from multiple viewpoints to improve mapping quality.

### My contributions include:
- Object detection.
- Sensor fusion and integration.
- Dense background map generation.

<figure style="text-align: center;">
  <img src="../../images/semantic_mapping/lidar_cam_fusion.png" alt="LiDAR Camera Fusion" style="max-width: 100%; margin: 0 auto;" />
  <figcaption style="font-style: italic;">Figure 3: LiDAR-Camera Fusion Result</figcaption>
</figure>


## Results

The system was tested in diverse environments, including industrial and simulated settings. The results demonstrate:
- High accuracy in **object detection** and reconstruction.
- Reliable mapping quality by avoiding sensor inconsistencies.
- Improved object-level understanding compared to traditional exploration methods.

<figure style="text-align: center; margin: 0;">
  <img src="../../images/semantic_mapping/simulated_setting.png" alt="Simulated Setting Mapping" style="max-width: 100%; margin: 0 auto;" />
  <figcaption style="font-style: italic; margin-top: 8px;">Figure 4: Mapping in Simulated Warehouse Settings</figcaption>
</figure>

<figure style="text-align: center; margin: 0;">
  <img src="../../images/semantic_mapping/industrial_setting.png" alt="Industrial Setting Mapping" style="max-width: 100%; margin: 0 auto;" />
  <figcaption style="font-style: italic; margin-top: 8px;">Figure 5: Mapping in Industry Office Settings</figcaption>
</figure>


## Discussion

The study highlights the advantages of using legged robots for semantic mapping, particularly in environments where traditional robots face limitations. The incorporation of object-level maps enables a more comprehensive understanding of the environment, supporting tasks such as structural inspection and operational planning.

### Challenges:
- Optimizing sensor integration for better real-time performance.
- Handling dynamic environments and distinguishing moving objects from static maps.

### Future Work:
- Improving sensor fusion accuracy.
- Incorporating dynamic object segmentation into static background maps.


## Conclusion

The use of a legged robot for semantic mapping offers significant advancements in robotics, enabling detailed, object-level understanding in complex environments. This project paves the way for more efficient exploration and operational planning in critical fields like construction and infrastructure inspection.
