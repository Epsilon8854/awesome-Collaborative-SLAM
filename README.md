# awesome-Collaborative-SLAM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Collaborative SLAM on multi-agent system**, inspired by [Awesome-Implicit-NeRF-SLAM](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM) <br>

#### Please feel free to send me [pull requests](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM/blob/main/how-to-PR.md) or [email](mailto:epsilon8854@unist.ac.kr) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

For an overview of **Collabortive SLAM**, checkout the Survey ([Towards Collaborative Simultaneous Localization and Mapping: a Survey of the Current Research Landscape](https://arxiv.org/abs/2108.08325) and  and Collection ([awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF))

---

## Overview
  - [Overview](#overview)
  - [Centralized SLAM](#centralized-slam)
    <!-- - [Visual](#visual)
    - [Lidar](#lidar)
    - [Multimodal](#multimodal) -->
  - [Decentralized SLAM](#decentralized-slam)
    <!-- - [Visual](#visual-1)
    - [Lidar](#lidar-1)
    - [Multimodal](#multimodal-1) -->
  <!-- - [Platform](#platform) -->
  <!-- <!-- - [Environments](#environments) -->
  - [Datasets](#datasets)

---

## Centralized SLAM
All data from individual robots or sensors are sent to a central server or unit. The central server processes the data to create a unified map and determine each robot's location. 
  <!-- ### Visual -->
  * **CCM-SLAM**: Robust and efficient centralized collaborative monocular simultaneous localization and mapping for robotic team *JFR, 2019* [[Paper](https://www.research-collection.ethz.ch/handle/20.500.11850/313259)] [[Code](https://github.com/VIS4ROB-lab/ccm_slam?tab=readme-ov-file)]
  * **COVINS-G**: A Generic Back-end for Collaborative Visual-Inertial SLAM, *ICRA, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9585827)] [[Code](https://github.com/VIS4ROB-lab/covins)]
  <!-- ### Lidar -->

  <!-- ### Multimodal -->


## Decentralized SLAM
Each robot operates independently, creating its own map and determining its own location. Robots may occasionally share map information with others upon encounter.
   <!-- ### Visual -->
  * **DOOR-SLAM**: Distributed, Online, and Outlier Resilient SLAM for Robotic Teams *RA-L, 2020* [[Paper](https://arxiv.org/abs/1909.12198)] [[Code](https://github.com/MISTLab/DOOR-SLAM)]
  <!-- ### Lidar -->
  <!-- ### Multimodal -->
  * **Swarm-SLAM**:Sparse Decentralized Collaborative Simultaneous Localization and Mapping Framework for Multi-Robot Systems, *RA-L, 2024*. [[Paper](https://arxiv.org/abs/2301.06230)] [[Code](https://github.com/MISTLab/Swarm-SLAM)]

## Distributed SLAM
A hybrid approach that involves collaborative effort among multiple agents or robots. Robots collect data and perform their own localization and mapping, but also communicate and share information with each other to build a comprehensive global map.
  <!-- ### Visual -->
  <!-- ### Lidar -->
  * **Kimera-multi**: Robust, distributed, dense metric-semantic slam for multi-robot systems *T-RO 2022* [[Paper](http://ieeexplore.ieee.org/abstract/document/9686955)] [[Code](https://github.com/MIT-SPARK/Kimera-Multi)]
  * **DiSCo-SLAM**: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization *RA-L, 2022* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
  * **DCL-SLAM**: Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm, *Sensors, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10375928)] [[Code](https://github.com/PengYu-Team/DCL-SLAM)]
  <!-- ### Multimodal -->

<!-- ## Platform

## Environments -->

## Datasets
  * **S3E**: A Large-scale Multimodal Dataset for Collaborative SLAM, *arXiv, 2022* [[Paper](https://arxiv.org/abs/2210.13723)] [[Code](https://github.com/PengYu-Team/S3E)]
  * **GRACO**: A Multimodal-Heterogeneous Dataset for Ground and Aerial Cooperative Localization and Mapping, *RA-L, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10008011)] [[Code](https://github.com/SYSU-RoboticsLab/GrAco?tab=readme-ov-file#a-multimodal-heterogeneous-dataset-for-ground-and-aerial-cooperative-localization-and-mapping)]
  * **Kimera-Multi-Data**: Resilient and Distributed Multi-Robot Visual SLAM: Datasets, Experiments, and Lessons Learned  *arxiv, 2023* [[Paper](https://arxiv.org/abs/2304.04362)] [[Code](https://github.com/MIT-SPARK/Kimera-Multi-Data)]
