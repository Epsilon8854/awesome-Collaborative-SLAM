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
  - [Platform](#platform)
  - [Environments](#environments)
  - [Datasets](#datasets)

---

## Centralized SLAM
In Centralized SLAM, there is typically a central computational unit or system that processes and integrates all the data collected by various agents.
  <!-- ### Visual -->
  * **COVINS-G**: A Generic Back-end for Collaborative Visual-Inertial SLAM, *ICRA, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9585827)] [[Code](https://github.com/VIS4ROB-lab/covins)]
  <!-- ### Lidar -->

  <!-- ### Multimodal -->


## Decentralized SLAM
Decentralized SLAM also involves multiple agents, but it emphasizes the autonomy of each agent in the mapping process. There is no central coordination or data integration point.
  <!-- ### Visual -->
  * **DOOR-SLAM**: Distributed, Online, and Outlier Resilient SLAM for Robotic Teams *RA-L, 2020* [[Paper](https://arxiv.org/abs/1909.12198)] [[Code](https://github.com/MISTLab/DOOR-SLAM)]
  <!-- ### Lidar -->
  <!-- ### Multimodal -->
  * **Swarm-SLAM**:Sparse Decentralized Collaborative Simultaneous Localization and Mapping Framework for Multi-Robot Systems, *RA-L, 2024*. [[Paper](https://arxiv.org/abs/2301.06230)] [[Code](https://github.com/MISTLab/Swarm-SLAM)]

## Distributed SLAM
In a distributed SLAM system, multiple agents (robots or sensors) work together to map an environment. Each agent collects data and shares it with others. Therefore, both centralized and decentralized methods can be distributed. In this category, SLAMs that deal with distributed systems regardless of whether they are decentralized or centralized are described.
  <!-- ### Visual -->
  <!-- ### Lidar -->
  * **DiSCo-SLAM**: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization *RA-L, 2022* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
  * **DCL-SLAM**: Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm, *Sensors, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10375928)] [[Code](https://github.com/PengYu-Team/DCL-SLAM)]
  <!-- ### Multimodal -->

<!-- ## Platform

## Environments -->

## Datasets
  * **S3E**: A Large-scale Multimodal Dataset for Collaborative SLAM, *arXiv, 2022* [[Paper](https://arxiv.org/abs/2210.13723)] [[Code](https://github.com/PengYu-Team/S3E)]
  * **GRACO**: A Multimodal-Heterogeneous Dataset for Ground and Aerial Cooperative Localization and Mapping, *RA-L, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10008011)] [[Code](https://github.com/SYSU-RoboticsLab/GrAco?tab=readme-ov-file#a-multimodal-heterogeneous-dataset-for-ground-and-aerial-cooperative-localization-and-mapping)]
  * **Kimera-Multi-Data**: Resilient and Distributed Multi-Robot Visual SLAM: Datasets, Experiments, and Lessons Learned  *arxiv, 2023* [[Paper](https://arxiv.org/abs/2304.04362)] [[Code](https://github.com/MIT-SPARK/Kimera-Multi-Data)]
