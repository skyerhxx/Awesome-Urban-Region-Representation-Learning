<!-- [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models/graphs/commit-activity) -->
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models)
<!-- <img alt="GitHub watchers" src="https://img.shields.io/github/watchers/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models?style=social"> <img alt="GitHub stars" src="https://img.shields.io/github/stars/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models?style=social"> <img alt="GitHub forks" src="https://img.shields.io/github/forks/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models?style=social"> -->

# <p align=center>`Awesome Urban Region Representation Learning`</p>

:star2:**A collection of papers, datasets, benchmarks, code, and pre-trained weights for Urban Region Representation Learning Models.**

## 📢 Latest Updates
<!-- :fire::fire::fire: Last Updated on 2024.08.19 :fire::fire::fire: -->

- **2024.9.08**: Initiate project.

## Urban Region Representation Learning
Other names: Urban Region Profiling / Urban Region Embedding / Urban Indicator Prediction
|Abbreviation|Title|Publication|Paper|Modality|Code & Weights|
|:---:|---|:---:|:---:|:---:|:---:|
|HDGE|Region Representation Learning via Mobility Flow|CIKM2017||Mobility||
|ZE-Mob|Representing Urban Functions through Zone Embedding with Human Mobility Patterns|IJCAI2018|[Paper](https://www.ijcai.org/Proceedings/2018/0545.pdf)|||
|CDAE|Learning Urban Community Structures: A Collective Embedding Perspective with Periodic Spatial-temporal Mobility Graphs|ACM TITS2018||||
|RegionEncoder|Unsupervised Representation Learning of Spatial Data via Multimodal Embedding|CIKM2019|[Paper](https://dl.acm.org/doi/pdf/10.1145/3357384.3358001)|||
||Beyond Geo-First Law: Learning Spatial Representations via Integrated Autocorrelations and Complementarity|ICDM2019||||
|Tile2Vec|Tile2Vec: Unsupervised Representation Learning for Spatially Distributed Data|AAAI2019|[Paper](https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.33013967)|Satellite img||
|MV-PN|Efficient Region Embedding with Multi-View Spatial Networks: A Perspective of Locality-Constrained Spatial Autocorrelations|AAAI2019|[Paper](https://dl.acm.org/doi/pdf/10.1609/aaai.v33i01.3301906)|POI + Mobility||
||Learning to Interpret Satellite Images in Global Scale Using Wikipedia|IJCAI2019|          [Paper](https://arxiv.org/pdf/1905.02506)           |||
|CGAL|Unifying Inter-region Autocorrelation and Intra-region Structures for Spatial Embedding via Collective Adversarial Learning|KDD2019|[Paper]([dl.acm.org/doi/pdf/10.1145/3292500.3330972](https://dl.acm.org/doi/pdf/10.1145/3292500.3330972))|||
|Urban2Vec|Urban2Vec: Incorporating Street View Imagery and POIs for Multi-Modal Urban Neighborhood Embedding|AAAI2020|[Paper](https://arxiv.org/pdf/2001.11101)|Street-view img + POI (with rating & comments)||
|GMEL|Learning Geo-Contextual Embeddings for Commuting Flow Prediction|AAAI2020|[Paper](https://cdn.aaai.org/ojs/5425/5425-13-8650-1-10-20200511.pdf)|||
|READ|Lightweight and Robust Representation of Economic Scales from Satellite Imagery|AAAI2020|[Paper](https://aaai.org/papers/00428-lightweight-and-robust-representation-of-economic-scales-from-satellite-imagery/)|Satellite img||
||Predicting Economic Growth by Region Embedding: A Multigraph Convolutional Network Approach|CIKM2020|[Paper]([dl.acm.org/doi/pdf/10.1145/3340531.3411882](https://dl.acm.org/doi/pdf/10.1145/3340531.3411882))|||
||Learning to Score Economic Development from Satellite Imagery|KDD2020|[Paper]([dl.acm.org/doi/pdf/10.1145/3394486.3403347](https://dl.acm.org/doi/pdf/10.1145/3394486.3403347))|||
|MVURE|Multi-View Joint Graph Representation Learning for Urban Region Embedding|IJCAI2020|[Paper](https://www.ijcai.org/Proceedings/2020/0611.pdf)|POI + Mobility + Check-in||
|SceneParse|Predicting Livelihood Indicators from Community-Generated Street-Level Imagery|AAAI2021|[Paper](https://arxiv.org/pdf/2006.08661)|Street-view img||
|M3G|Learning Neighborhood Representation from Multi-Modal Multi-Graph: Image, Text, Mobility Graph and Beyond|AAAI2021|[Paper](https://arxiv.org/pdf/2105.02489)|||
|HUGAT|Effective Urban Region Representation Learning Using Heterogeneous Urban Graph Attention Network (HUGAT)|arxiv2022||||
|PG-SimCLR|Beyond the First Law of Geography: Learning Representations of Satellite Imagery by Leveraging Point-of-Interests|WWW2022|[Paper](https://dl.acm.org/doi/pdf/10.1145/3485447.3512149)|Satellite img + POI||
||Predicting Multi-level Socioeconomic Indicators from Structural Urban Imagery|CIKM2022|[Paper](https://dl.acm.org/doi/pdf/10.1145/3511808.3557153)|Satellite img + Street-view img (+ Road Network)||
|Region2Vec|Urban Region Profiling via Multi-Graph Representation Learning|CIKM2022|[Paper]([dl.acm.org/doi/pdf/10.1145/3511808.3557720](https://dl.acm.org/doi/pdf/10.1145/3511808.3557720))|||
|MGFN|Multi-Graph Fusion Networks for Urban Region Embedding|IJCAI2022|[Paper](https://arxiv.org/pdf/2201.09760)|Mobility||
|URGENT|Urban Region Profiling With Spatio-Temporal Graph Neural Networks|IEEE TCSS 2022|[Paper](https://ieeexplore.ieee.org/document/9805695)|POI + Mobility||
|ReMVC|Region Embedding with Intra and Inter-View Contrastive Learning|TKDE2022|[Paper](https://arxiv.org/pdf/2211.08975)|POI + Mobility||
|KnowCL|Knowledge-infused Contrastive Learning for Urban Imagery-based Socioeconomic Prediction|WWW2023|[Paper](https://dl.acm.org/doi/pdf/10.1145/3543507.3583876)|Satellite img + Knowledge Graph||
|Geo-Tile2Vec|Geo-Tile2Vec: A Multi-Modal and Multi-Stage Embedding Framework for Urban Analytics|ACM TSAS 2023|[Paper](https://dl.acm.org/doi/pdf/10.1145/3571741)|||
|HREP|Heterogeneous Region Embedding with Prompt Learning|AAAI2023|[Paper](https://dl.acm.org/doi/abs/10.1609/aaai.v37i4.25625)|POI + Mobility||
|RegionDCL|Urban Region Representation Learning with OpenStreetMap Building Footprints|KDD2023|[Paper]([dl.acm.org/doi/pdf/10.1145/3580305.3599538](https://dl.acm.org/doi/pdf/10.1145/3580305.3599538))|OpenStreetMap (Building Footprint + POI)||
||Learning Region Similarities via Graph-Based Deep Metric Learning|TKDE2023||||
||Urban visual intelligence: Uncovering hidden city profiles with street view images|PNAS2023|[Paper]([pnas.org/doi/pdf/10.1073/pnas.2220417120](https://www.pnas.org/doi/pdf/10.1073/pnas.2220417120))|Street-view img + POI||
|HGI|Learning urban region representations with POIs and hierarchical graph infomax|JPRS2023|[Paper](https://www.sciencedirect.com/science/article/pii/S0924271622003148)|POI||
|MMGR|Geographic mapping with unsupervised multi-modal representation learning from VHR images and POIs|JPRS2023|[Paper](https://www.sciencedirect.com/science/article/pii/S0924271623001235)|Satellite img + POI||
|ROMER|Region-Wise Attentive Multi-View Representation Learning for Urban Region Embeddings|CIKM2023|[Paper]([dl.acm.org/doi/pdf/10.1145/3583780.3615194](https://dl.acm.org/doi/pdf/10.1145/3583780.3615194))|POI + Mobility + Check-in||
|HAFusion|Urban Region Representation Learning with Attentive Fusion|ICDE2024|[Paper](https://arxiv.org/pdf/2312.04606)|POI + Mobility + Land use||
|ReCP|Urban Region Embedding via Multi-View Contrastive Prediction|AAAI2024|[Paper](https://arxiv.org/pdf/2312.09681)|POI + Mobility||
|MuseCL|MuseCL: Predicting Urban Socioeconomic Indicators via Multi-Semantic Contrastive Learning|IJCAI2024|[Paper](https://arxiv.org/pdf/2407.09523)|Satellite img + Street-view img + POI + Mobility||
|CGAP|CGAP: Urban Region Representation Learning with Coarsened Graph Attention Pooling|IJCAI2024|[Paper](https://www.ijcai.org/proceedings/2024/0832.pdf)|POI + Mobility||
|UrbanCLIP|UrbanCLIP: Learning Text-enhanced Urban Region Profiling with Contrastive Language-Image Pretraining from the Web|WWW2024|[Paper]([dl.acm.org/doi/pdf/10.1145/3589334.3645378](https://dl.acm.org/doi/pdf/10.1145/3589334.3645378))|Satellite img + Text (generated)||
|UrbanVLP|UrbanVLP: Multi-Granularity Vision-Language Pretraining for Urban Region Profiling|arxiv2024|[Paper](https://arxiv.org/pdf/2403.16831)|Satellite img + Street-view img + Text (generated)||
|CityFM|City Foundation Models for Learning General Purpose Representations from OpenStreetMap|CIKM2024|[Paper](https://arxiv.org/pdf/2310.00583)|OSM data (Node,Way,Relation)(tags as textual annotations)||
|MTE|Urban region representation learning with human trajectories: a multi-view approach incorporating transition, spatial, and temporal perspectives|GISR2024||Trajectory||
|ReFound|ReFound: Crafting a Foundation Model for Urban Region Understanding upon Language and Visual Foundations|KDD2024|[Paper]([dl.acm.org/doi/pdf/10.1145/3637528.3671992](https://dl.acm.org/doi/pdf/10.1145/3637528.3671992))|Satellite img + POI||
|USPM|Profiling Urban Streets: A Semi-Supervised Prediction Model Based on Street View Imagery and Spatial Topology|KDD2024|[Paper]([dl.acm.org/doi/pdf/10.1145/3637528.3671918](https://dl.acm.org/doi/pdf/10.1145/3637528.3671918))|Street-view img + Text (generated)||





## Related Links
[Awesome-Spatio-Temporal-Representation-Learning: Summary of Spatio-Temporal Representation Learning Models](https://github.com/aptx1231/Awesome-Spatio-Temporal-Representation-Learning)

[Awesome-Multimodal-Urban-Computing](https://github.com/CityMind-Lab/Awesome-Multimodal-Urban-Computing)

[Awesome-Urban-Foundation-Models](https://github.com/usail-hkust/Awesome-Urban-Foundation-Models)