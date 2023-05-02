# <img src='image/logo-radar-camera-fusion.png' height=30 />  Awesome-Radar-Camera-Fusion 
Website: [https://XJTLU-VEC.github.io/Radar-Camera-Fusion](https://xjtlu-vec.github.io/Radar-Camera-Fusion)

## Overview
- [Datasets](#Datasets)
- [Methods](#Methods)
- [Citation](#Citation)

## Datasets
| Id | Name             | Year | Task                                                                                                      | Annotation                     | Radar Data Representation                                   | Link                                                         |
|----|------------------|------|-----------------------------------------------------------------------------------------------------------|--------------------------------|-------------------------------------------------------------|--------------------------------------------------------------|
| 1  | nuScenes         | 2019 | Object Detection<br>Object Tracking                                                                       | 3D box-level                   | Point Cloud                                                 | [Website](https://www.nuscenes.org/nuscenes) [Github](https://github.com/nutonomy/nuscenes-devkit)                           |
| 2  | Astyx            | 2019 | Object Detection                                                                                          | 3D box-level                   | Point Cloud                                                 | [Website](http://www.astyx.net)                                         |
| 3  | SeeingThroughFog | 2020 | Object Detection                                                                                          | 2D box-level<br>3D box-level   | Point Cloud                                                 | [Website](https://www.uni-ulm.de/en/in/driveu/projects/dense-datasets/) |
| 4  | CARRADA          | 2020 | Object Detection<br>Semantic Segmentation<br>Object Tracking<br>Trajectory Prediction                     | 2D box-level<br>2D pixel-level | Range-Doppler Tensor<br>Range-Azimuth Tensor                | [Website](https://arthurouaknine.github.io/codeanddata/carrada)                                                             |
| 5  | HawkEye          | 2020 | Semantic Segmentation                                                                                     | 3D point-level                 | Point Cloud                                                 | [Website](https://jguan.page/HawkEye/)                                                             |
| 6  | Zendar           | 2020 | Object Detection<br>Mapping<br>Localization                                                               | 2D box-level                   | Range-Doppler Tensor<br>Range-Azimuth Tensor<br>Point Cloud | [Website](http://zendar.io/dataset)                                                          |
| 7  | RADIATE          | 2020 | Object Detection<br>Object Tracking<br>SLAM<br>Scene Understanding                                        | 2D box-level                   | Range-Azimuth Tensor                                        | [Website](http://pro.hw.ac.uk/radiate/)                                                            |
| 8  | AIODrive         | 2020 | Object Detection<br>Object Tracking<br>Semantic Segmentation<br>Trajectory Prediction<br>Depth Estimation | 2D box-level<br>3D box-level   | Point Cloud                                                 | [Website](http://www.aiodrive.org/)                                                            |
| 9  | CRUW             | 2021 | Object Detection                                                                                          | 2D box-level                   | Range-Azimuth Tensor                                        | [Website](https:/www.cruwdataset.org/)                                                             |
| 10 | RaDICaL          | 2021 | Object Detection                                                                                          | 2D box-level                   | ADC Signal                                                  | [Website](https://publish.illinois.edu/radicaldata/)                                                             |
| 11 | RadarScenes | 2021 | Object Detection<br>Semantic Segmentation    | 2D pixel-level<br>3D point-level | Point Cloud                                                                                               |  [Website](https://radar-scenes.com/) |
| 12 | RADDet      | 2021 | Object Detection                             | 2D box-level<br>3D box-level     | Range-Azimuth-Doppler Tensor                                                                                              |  [Github](https://github.com/ZhangAoCanada/RADDet) |
| 13 | FloW        | 2021 | Object Detection                             | 2D box-level                     | Range-Doppler Tensor<br>Point Cloud                                                                                               | [Website](https://orca-tech.cn/datasets/FloW/Introduction) [Github](https://github.com/ORCA-Uboat/FloW-Dataset)  |
| 14 | RADIal      | 2021 | Object Detection<br>Semantic Segmentation    | 2D box-level                     | ADC Signal<br>Range-Azimuth-Doppler Tensor<br>Range-Azimuth Tensor<br>Range-Doppler Tensor<br>Point Cloud             |  [Github](https://github.com/valeoai/RADIal) |
| 15 | VoD         | 2022 | Object Detection                             | 2D box-level<br>3D box-level     | Point Cloud                                                                                                         | [Website](https://tudelft-iv.github.io/view-of-delft-dataset/)  |
| 16 | Boreas      | 2022 | Object Detection<br>Localization<br>Odometry | 2D box-level                     | Range-Azimuth Tensor                                                                                                  |  [Website](https://www.boreas.utias.utoronto.ca/) |
| 17 | TJ4DRadSet  | 2022 | Object Detection<br>Object Tracking          | 3D box-level                     | Point Cloud                                                                                                               | [Website](https://github.com/TJRadarLab/TJ4DRadSet)  |
| 18 | K-Radar     | 2022 | Object Detection<br>Object Tracking<br>SLAM  | 3D box-level                     | Range-Azimuth-Doppler Tensor                                                                                                         | [Github](https://github.com/kaist-avelab/k-radar)  |
| 19 | aiMotive    | 2022 | Object Detection                             | 3D box-level                     | Point cloud                                                                                                                       |  [Website](https://github.com/aimotive/aimotive_dataset) |

## Methods
| Id | Short Name       | Year | Task                                      | Annotation                     | Radar Data Representation | Fusion Level  | Dataset                         | Link                                    |
|----|------------------|------|-------------------------------------------|--------------------------------|---------------------------|---------------|---------------------------------|------------------------------------------------|
| 1  | Chadwick et al.  | 2019 | Object Detection                          | 2D box-level                   | Point Cloud               | Feature Level | Self-Recorded                   |                                                |
| 2  | RRPN             | 2019 | Object Detection                          | 2D box-level                   | Point Cloud               | Data Level    | nuScenes                        | [Code](https://github.com/mrnabati/RRPN)               |
| 3  | Jha et al.       | 2019 | Object Detection                          | 2D box-level                   | Point Cloud               | Object Level  | Self-Recorded                   |                                                |
| 4  | CMGGAN           | 2019 | Semantic Segmentation                     | 2D point-level                 | Grid Map                  | Feature Level | Self-Recorded                   |                                                |
| 5  | Meyer and Kuschk | 2019 | Object Detection                          | 3D box-level                   | Point Cloud               | Data Level    | Astyx                           |                                                |
| 6  | RVNet            | 2019 | Object Detection                          | 2D box-level                   | Point Cloud               | Feature Level | nuScenes                        |                                                |
| 7  | FusionNet        | 2019 | Object Detection<br>Object Classification | 2D box-level                   | Range-Azimuth Tensor      | Feature Level | Self-Recorded                   |                                                |
| 8  | SO-Net           | 2020 | Object Detection<br>Semantic Segmentation | 2D box-level<br>2D pixel-level | Point Cloud               | Feature Level | nuScenes                        |                                                |
| 9  | SAF-FCOS         | 2020 | Object Detection                          | 2D box-level                   | Point Cloud               | Feature Level | nuScenes                        | [Code](https://github.com/Singingkettle/SAF-FCOS)      |
| 10 | CRF-Net          | 2019 | Object Detection                          | 2D box-level                   | Point Cloud               | Data Level    | nuScenes <br> Self-Recorded | [Code](https://github.com/TUMFTM/CameraRadarFusionNet) |
| 11 | Bijelic et al. | 2020 | Object Detection                 | 2D box-level | Point Cloud                  | Feature Level | DENSE         | [Code](https://github.com/princeton-computational-imaging/SeeingThroughFog)            |
| 12 | BIRANet        | 2020 | Object Detection                 | 2D box-level | Point Cloud                  | Feature Level | nuScenes      | [Code](https://github.com/RituYadav92/Radar-RGB-Attentive-Multimodal-Object-Detection) |
| 13 | Nabati and Qi  | 2020 | Object Detection<br>Depth Estimation | 2D box-level | Point Cloud              | Mixed Level   | nuScenes      |                                                                                |
| 14 | YOdar          | 2020 | Object Detection                 | 2D box-level | Point Cloud                  | Feature Level | nuScenes      |                                                                                |
| 15 | CenterNet      | 2020 | Object Detection                 | 3D box-level | Point Cloud                  | Feature Level | nuScenes      | [Code](https://github.com/mrnabati/CenterFusion)                                       |
| 16 | RODNet         | 2020 | Object Detection                 | 2D box-level | Range-Azimuth Tensor         | Feature Level | CRUW          | [Code](https://github.com/yizhou-wang/RODNet)                                          |
| 17 | RAMP-CNN       | 2021 | Object Detection                 | 2D box-level | Range-Azimuth-Doppler Tensor | Feature Level | CRUW          |                                                                                |
| 18 | Li and Xie     | 2021 | Object Detection                 | 3D box-level | Point Cloud                  | Feature Level | nuScenes      |                                                                                |
| 19 | Kim et al.     | 2020 | Object Detection                 | 3D box-level | Range-Azimuth Tensor         | Feature Level | Self-Recorded |                                                                                |
| 20 | AssociationNet | 2021 | Object Detection                 | 2D box-level | Point Cloud                  | Object Level  | Self-Recorded |                                                                                |
| 21 | RVF-Net        | 2021 | Object Detection      | 3D box-level               | Point Cloud                         | Data Level    | nuScenes                       |             |
| 22 | Cui et al.     | 2021 | Object Detection      | 3D box-level               | Point Cloud                         | Mixed Level   | Astyx                          |             |
| 23 | RISFNet        | 2021 | Object Detection      | 2D box-level               | Point Cloud                         | Feature Level | FloW                           |             |
| 24 | GRIF Net       | 2021 | Object Detection      | 3D box-level               | Point Cloud                         | Feature Level | nuScenes                       |             |
| 25 | Stacker et al. | 2021 | Object Detection      | 2D box-level               | Point Cloud                         | Feature Level | nuScenes                       |             |
| 26 | Harley et al.  | 2021 | Semantic Segmentation | 2D pixel-level             | Point Cloud                         | Feature Level | nuScenes                       |             |
| 27 | RadSegNet      | 2022 | Object Detection      | 2D box-level<br>2D pixel-level | Point Cloud<br>Range-Azimuth Tensor | Data-Level    | Astyx<br>RADIATE               |             |
| 28 | RCBEV          | 2022 | Object Detection      | 3D box-level               | Point Cloud                         | Feature Level | nuScenes                       |             |
| 29 | CRAFT          | 2022 | Object Detection      | 3D box-level               | Point Cloud                         | Data Level    | nuScenes                       |             |
| 30 | DeepFusion     | 2022 | Object Detection      | 3D box-level               | Point Cloud                         | Feature Level | Self-reorded <br> nuScenes |             |
| 31 | CramNet    | 2022 | Object Detection | 3D box-level | Range-Azimuth Tensor      | Feature Level | RADIATE  |             |
| 32 | MVFusion   | 2023 | Object Detection | 3D box-level | Point Cloud               | Feature Level | nuScenes |             |
| 33 | CRN        | 2023 | Object Detection | 3D box-level | Point Cloud               | Feature Level | nuScenes |             |


## Citation
Please use the following citation when referencing
```
@article{yao2023radar,
  title={Radar-Camera Fusion for Object Detection and Semantic Segmentation in Autonomous Driving: A Comprehensive Review},
  author={Yao, Shanliang and Guan, Runwei and Huang, Xiaoyu and Li, Zhuoxiao and Sha, Xiangyu and Yue, Yong and Lim, Eng Gee and Seo, Hyungjoon and Man, Ka Lok and Zhu, Xiaohui and others},
  journal={arXiv preprint arXiv:2304.10410},
  year={2023}
}
```
