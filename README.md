# awesome-Collaborative-SLAM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Collaborative SLAM on multi-agent system**, inspired by [Awesome-Implicit-NeRF-SLAM](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM) <br>

#### Please feel free to send me [pull requests](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM/blob/main/how-to-PR.md) or [email](mailto:epsilon8854@unist.ac.kr) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

For an overview of **Collabortive SLAM**, checkout the Survey ([Towards Collaborative Simultaneous Localization and Mapping: a Survey of the Current Research Landscape](https://arxiv.org/abs/2108.08325) and  and Collection ([awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF))

---

## Overview

  - [Centralized SLAM](#centralized-slam)

  - [Decentralized SLAM](#decentralized-slam)

  - [Distributed SLAM](#distributed-slam)
  <!-- - [Platform](#platform) -->
  <!-- <!-- - [Environments](#environments) -->
  - [Datasets](#datasets)


---

## Centralized SLAM
All data from individual robots or sensors are sent to a central server or unit. The central server processes the data to create a unified map and determine each robot's location. 
  <!-- ### Visual -->
  * **CCM-SLAM**: Robust and efficient centralized collaborative monocular simultaneous localization and mapping for robotic team *JFR, 2019* [[Paper](https://www.research-collection.ethz.ch/handle/20.500.11850/313259)] [[Code](https://github.com/VIS4ROB-lab/ccm_slam?tab=readme-ov-file)]
  * **COVINS-G**: A Generic Back-end for Collaborative Visual-Inertial SLAM, *ICRA, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9585827)] [[Code](https://github.com/VIS4ROB-lab/covins)]
  * **CP-SLAM**: Collaborative Neural Point-based SLAM System *arxiv 2023* [[Paper](https://arxiv.org/abs/2311.08013)] [[Code](https://github.com/VIS4ROB-lab/covins)]
  <!-- ### Lidar -->

  <!-- ### Multimodal -->


## Decentralized SLAM
Each robot operates independently, creating its own map and determining its own location. Robots may occasionally share map information with others upon encounter.
   <!-- ### Visual -->
  * **DOOR-SLAM**: Distributed, Online, and Outlier Resilient SLAM for Robotic Teams, *RA-L, 2020* [[Paper](https://arxiv.org/abs/1909.12198)] [[Code](https://github.com/MISTLab/DOOR-SLAM)]
  * **CoVOR-SLAM**: Cooperative SLAM using Visual Odometry and Ranges for Multi-Robot Systems, *arxiv 2023*[[paper](https://arxiv.org/abs/2311.12580)]

  <!-- ### Lidar -->
  <!-- ### Multimodal -->
  * Cross-Agent Relocalization for Decentralized Collaborative SLAM, *ICRA, 2023*. [[Paper](https://ieeexplore.ieee.org/abstract/document/10160941)] [[Code](https://github.com/VIS4ROB-lab/decoSLAM)]  
  * **Swarm-SLAM**:Sparse Decentralized Collaborative Simultaneous Localization and Mapping Framework for Multi-Robot Systems, *RA-L, 2024*. [[Paper](https://arxiv.org/abs/2301.06230)] [[Code](https://github.com/MISTLab/Swarm-SLAM)]
  * **Multi S-Graphs**:an Efficient Real-time Distributed Semantic-Relational Collaborative SLAM, *arxiv, 2024* [[Paper](https://arxiv.org/abs/2401.05152)] [[Code](https://github.com/snt-arg/multi_s_graphs_docker)]

## Distributed SLAM
In a distributed system, the processing is spread across multiple nodes or agents. Robots collect data and perform their own localization and mapping, but also communicate and share information with each other to build a comprehensive global map. This could be peer-to-peer or via a central hub.
  <!-- ### Visual -->
  <!-- ### Lidar -->
  * **Kimera-multi**: Robust, distributed, dense metric-semantic slam for multi-robot systems, *T-RO, 2022* [[Paper](http://ieeexplore.ieee.org/abstract/document/9686955)] [[Code](https://github.com/MIT-SPARK/Kimera-Multi)]
  * **DiSCo-SLAM**: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization, *RA-L, 2022* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
  * **SEAL**: Simultaneous Exploration and Localization in Multi-Robot Systems, *arxiv, 2023* [[Paper](https://arxiv.org/pdf/2306.12623.pdf)] 
  * **DCL-SLAM**: Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm, *Sensors, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10375928)] [[Code](https://github.com/PengYu-Team/DCL-SLAM)]
  * **RING++**: Roto-Translation Invariant Gram for Global Localization on a Sparse Scan Map, *T-RO, 2023*[[Paper](https://ieeexplore.ieee.org/document/10224330)] [[Code1](https://github.com/lus6-Jenny/RING)] [[Code2](https://github.com/MaverickPeter/MR_SLAM)] 
  * **IRBCD** Distributed Pose-graph Optimization with Multi-level Partitioning for Collaborative SLAM, *arxiv, 2024*[[Paper](https://arxiv.org/abs/2401.01657)]
  <!-- ### Multimodal -->

<!-- ## Platform

## Environments -->

## Datasets
* **UTIAS** The UTIAS multi-robot cooperative localization and mapping dataset. *IJRR 2011* [[Paper](https://journals.sagepub.com/doi/abs/10.1177/0278364911398404] [[Project_page](http://asrl.utias.utoronto.ca/datasets/mrclam/)]
 * **Airmuseum**: a heterogeneous multi-robot dataset for stereo-visual and inertial simultaneous localization and mapping. *MFI, 2020* [[Paper](https://ieeexplore.ieee.org/abstract/document/9235257/)] [[Code](https://github.com/AirMuseumDataset/AirMuseumDataset)]
  * **S3E**: A Large-scale Multimodal Dataset for Collaborative SLAM, *arXiv, 2022* [[Paper](https://arxiv.org/abs/2210.13723)] [[Code](https://github.com/PengYu-Team/S3E)]
  * **GRACO**: A Multimodal-Heterogeneous Dataset for Ground and Aerial Cooperative Localization and Mapping, *RA-L, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10008011)] [[Code](https://github.com/SYSU-RoboticsLab/GrAco?tab=readme-ov-file#a-multimodal-heterogeneous-dataset-for-ground-and-aerial-cooperative-localization-and-mapping)]
  * **Kimera-Multi**: Resilient and Distributed Multi-Robot Visual SLAM: Datasets, Experiments, and Lessons Learned, *arxiv, 2023* [[Paper](https://arxiv.org/abs/2304.04362)] [[Code](https://github.com/MIT-SPARK/Kimera-Multi-Data)]
 