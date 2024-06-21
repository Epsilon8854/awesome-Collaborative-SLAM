# awesome-Collaborative-SLAM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Collaborative SLAM on multi-agent system**, inspired by [Awesome-Implicit-NeRF-SLAM](https://github.com/DoongLi/awesome-Implicit-NeRF-SLAM) <br>

#### Please feel free to send me [pull requests](https://github.com/Epsilon8854/awesome-Collaborative-SLAM/blob/main/how-to-PR.md) or [email](mailto:epsilon8854@unist.ac.kr) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

For an overview of **Collabortive SLAM**, checkout the Survey ([Towards Collaborative Simultaneous Localization and Mapping: a Survey of the Current Research Landscape](https://arxiv.org/abs/2108.08325) 

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
  * **CCM-SLAM**: Robust and efficient centralized collaborative monocular simultaneous localization and mapping for robotic team *JFR, 2019* [[Paper](https://www.research-collection.ethz.ch/handle/20.500.11850/313259)] [[Code](https://github.com/VIS4ROB-lab/ccm_slam?tab=readme-ov-file)]
  * **Edge robotics**: Edge-computing-accelerated multirobot simultaneous localization and mapping. *IoT-J, 2022* [[Paper](https://ieeexplore.ieee.org/abstract/document/9693970)]
  * **COVINS-G**: A Generic Back-end for Collaborative Visual-Inertial SLAM, *ICRA, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9585827)] [[Code](https://github.com/VIS4ROB-lab/covins)]
  * Robust Map Fusion with Visual Attention Utilizing Multi-agent Rendezvous,  *ICRA, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10161072)]
  * **AdaptSLAM**: Edge-Assisted Adaptive SLAM with Resource Constraints via Uncertainty Minimization, *INFOCOM, 2023* [[Paper](https://arxiv.org/abs/2301.04620)] [[Code](https://github.com/i3tyc/AdaptSLAM)]
  * **CP-SLAM**: Collaborative Neural Point-based SLAM System, *NeurIPS, 2024* [[Paper](https://arxiv.org/abs/2311.08013)] [[Code](https://github.com/VIS4ROB-lab/covins)]
  * **CoLRIO**: LiDAR-Ranging-Inertial Centralized State Estimation for Robotic Swarms, *ICRA, 2024* [[Paper](https://arxiv.org/abs/2402.11790)] [[Code](https://github.com/PengYu-team/Co-LRIO)]
  * Edge-Assisted Multi-Robot Visual-Inertial SLAM With Efficient Communication  *T-ASE, 2024* [[Paper](https://ieeexplore.ieee.org/abstract/document/10472967)]
  * **CCMD-SLAM**: Communication-Efficient Centralized Multi-Robot Dense SLAM with Real-Time Point Cloud Maintenance *TIM, 2024* [[Paper](https://ieeexplore.ieee.org/abstract/document/10530544)]
  
## Decentralized SLAM
Each robot operates independently, creating its own map and determining its own location. Robots may occasionally share map information with others upon encounter.
  * **Data-Efficient Decentralized Visual SLAM**  *ICRA, 2018* [[Paper](https://ieeexplore.ieee.org/abstract/document/8461155)] [[Code](https://github.com/uzh-rpg/dslam_open)]

  * **DOOR-SLAM**: Distributed, Online, and Outlier Resilient SLAM for Robotic Teams, *RA-L, 2020* [[Paper](https://arxiv.org/abs/1909.12198)] [[Code](https://github.com/MISTLab/DOOR-SLAM)]
  * **CoVOR-SLAM**: Cooperative SLAM using Visual Odometry and Ranges for Multi-Robot Systems, *arxiv, 2023*[[Paper](https://arxiv.org/abs/2311.12580)]

  * Cross-Agent Relocalization for Decentralized Collaborative SLAM, *ICRA, 2023*. [[Paper](https://ieeexplore.ieee.org/abstract/document/10160941)] [[Code](https://github.com/VIS4ROB-lab/decoSLAM)]  
  * **Swarm-SLAM**:Sparse Decentralized Collaborative Simultaneous Localization and Mapping Framework for Multi-Robot Systems, *RA-L, 2024*. [[Paper](https://arxiv.org/abs/2301.06230)] [[Code](https://github.com/MISTLab/Swarm-SLAM)]
  * **Multi S-Graphs**:an Efficient Real-time Distributed Semantic-Relational Collaborative SLAM, *RA-L, 2024* [[Paper](https://arxiv.org/abs/2401.05152)] [[Code](https://github.com/snt-arg/multi_s_graphs_docker)]

## Distributed SLAM
In a distributed system, the processing is spread across multiple nodes or agents. Robots collect data and perform their own localization and mapping, but also communicate and share information with each other to build a comprehensive global map. This could be peer-to-peer or via a central hub.
  * **CoSLAM**: Collaborative Visual SLAM in Dynamic Environments *TPAMI, 2013*[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6193110)] [[Code](https://github.com/danping/CoSLAM?tab=readme-ov-file)]
  * **DiSCo-SLAM**: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization *RA-L, 2021* [[Paper](https://ieeexplore.ieee.org/abstract/document/9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
  * Multirobot Collaborative Monocular SLAM Utilizing Rendezvous, *T-RO, 2021* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9381949)]
  * Distributed Ranging SLAM for Multiple Robots with Ultra-WideBand and Odometry Measurements *IROS, 2022* [[Paper](https://ieeexplore.ieee.org/abstract/document/9982028)]
  * **Kimera-multi**: Robust, distributed, dense metric-semantic slam for multi-robot systems, *T-RO, 2022* [[Paper](http://ieeexplore.ieee.org/abstract/document/9686955)] [[Code](https://github.com/MIT-SPARK/Kimera-Multi)]
  * **DiSCo-SLAM**: Distributed Scan Context-Enabled Multi-Robot LiDAR SLAM With Two-Stage Global-Local Graph Optimization, *RA-L, 2022* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9662965)] [[Code](https://github.com/RobustFieldAutonomyLab/DiSCo-SLAM)]
  * **DRACo-SLAM**: Distributed Robust Acoustic Communication-efficient SLAM for Imaging Sonar Equipped Underwater Robot Teams [[Paper](https://ieeexplore.ieee.org/abstract/document/9981822)] [[Code](https://github.com/jake3991/draco-slam)]
  * **SEAL**: Simultaneous Exploration and Localization in Multi-Robot Systems, *arxiv, 2023* [[Paper](https://arxiv.org/pdf/2306.12623.pdf)] 
  * **DCL-SLAM**: Distributed Collaborative LiDAR SLAM Framework for a Robotic Swarm, *Sensors, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10375928)] [[Code](https://github.com/PengYu-Team/DCL-SLAM)]
  * **RING++**: Roto-Translation Invariant Gram for Global Localization on a Sparse Scan Map, *T-RO, 2023* [[Paper](https://ieeexplore.ieee.org/document/10224330)] [[Code1](https://github.com/lus6-Jenny/RING)] [[Code2](https://github.com/MaverickPeter/MR_SLAM)] 
  * A Robot Web for DistributedMany-Device Localization *T-RO 2023* [[Paper](https://ieeexplore.ieee.org/abstract/document/10286058)]
  * **IRBCD** Distributed Pose-graph Optimization with Multi-level Partitioning for Collaborative SLAM, *arxiv, 2024* [[Paper](https://arxiv.org/abs/2401.01657)]
  * **Di-NeRF**: Distributed NeRF for Multi-Robot Collaborative Learning with Unknown Relative Poses *arxiv, 2024* [[Paper](https://arxiv.org/abs/2402.01485)]


  <!-- ### Multimodal -->

<!-- ## Platform

## Environments -->

## Datasets & Benchmarks
 * **UTIAS** The UTIAS multi-robot cooperative localization and mapping dataset. *IJRR, 2011* [[Paper](https://journals.sagepub.com/doi/abs/10.1177/0278364911398404] [[Project_page](http://asrl.utias.utoronto.ca/datasets/mrclam/)]
 * **Airmuseum**: a heterogeneous multi-robot dataset for stereo-visual and inertial simultaneous localization and mapping. *MFI, 2020* [[Paper](https://ieeexplore.ieee.org/abstract/document/9235257/)] [[Code](https://github.com/AirMuseumDataset/AirMuseumDataset)]

  * Ford Multi-AV Seasonal Dataset, *IJRR, 2020* [[Paper](https://github.com/Ford/AVData)] [[Code](https://journals.sagepub.com/doi/full/10.1177/0278364920961451)]
  * **S3E**: A Large-scale Multimodal Dataset for Collaborative SLAM, *arXiv, 2022* [[Paper](https://arxiv.org/abs/2210.13723)] [[Project_page](https://github.com/PengYu-Team/S3E)]
  * **GRACO**: A Multimodal-Heterogeneous Dataset for Ground and Aerial Cooperative Localization and Mapping, *RA-L, 2023* [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10008011)] [[Code](https://github.com/SYSU-RoboticsLab/GrAco?tab=readme-ov-file#a-multimodal-heterogeneous-dataset-for-ground-and-aerial-cooperative-localization-and-mapping)]
  
  * **Kimera-Multi**: Resilient and Distributed Multi-Robot Visual SLAM: Datasets, Experiments, and Lessons Learned, *arxiv, 2023* [[Paper](https://arxiv.org/abs/2304.04362)] [[Project_page](https://github.com/MIT-SPARK/Kimera-Multi-Data)]
  * **Customizable-SLAM**: Customizable Perturbation Synthesis for Robust SLAM Benchmarking, *arxiv, 2024* [[Paper](https://arxiv.org/abs/2402.08125)] [[Code](https://github.com/Xiaohao-Xu/SLAM-under-Perturbation)] 
  * **SubT-MRS Dataset**: Pushing SLAM Towards All-weather Environments *CVPR 2024* [[Paper](https://arxiv.org/pdf/2307.07607.pdf)] [[Project_page](https://sairlab.org/datasets/subtmrs)]

## Submodules
- Visual Place Recognition
  * Collaborative Visual Place Recognition through Federated Learning *CVPR 2024" [[Paper](https://openaccess.thecvf.com/content/CVPR2024W/FedVision-2024/html/Dutto_Collaborative_Visual_Place_Recognition_through_Federated_Learning_CVPRW_2024_paper.html)] 
