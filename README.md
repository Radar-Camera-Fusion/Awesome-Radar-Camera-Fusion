# <img src='image/logo-radar-camera-fusion.png' height=30 />  Awesome-Radar-Camera-Fusion 
Website: [https://XJTLU-VEC.github.io/Radar-Camera-Fusion](https://xjtlu-vec.github.io/Radar-Camera-Fusion)

## Overview
- [Datasets](#Datasets)
- [Methods](#Methods)
- [Citation](#Citation)

## Datasets
| Id | Name             | Year | Task                                                                                                      | Annotation                     | Radar Data Representation                                   |Affiliation| Link                                                         |
|----|------------------|------|-----------------------------------------------------------------------------------------------------------|--------------------------------|-------------------------------------------------------------|--------------------------------------------------------------|----|
| 1  | nuScenes         | 2019 | Object Detection<br>Object Tracking                                                                       | 3D box-level                   | Point Cloud                                                 | |[Website](https://www.nuscenes.org/nuscenes)                            |
| 2  | Astyx            | 2019 | Object Detection                                                                                          | 3D box-level                   | Point Cloud                                                 | |[Website](http://www.astyx.net)                                         |
| 3  | SeeingThroughFog | 2020 | Object Detection                                                                                          | 2D box-level<br>3D box-level   | Point Cloud                                                 | |[Website](https://www.uni-ulm.de/en/in/driveu/projects/dense-datasets/) |
| 4  | CARRADA          | 2020 | Object Detection<br>Semantic Segmentation<br>Object Tracking<br>Trajectory Prediction                     | 2D box-level<br>2D pixel-level | Range-Doppler Tensor<br>Range-Azimuth Tensor                |  |                                                            |
| 5  | HawkEye          | 2020 | Semantic Segmentation                                                                                     | 3D point-level                 | Point Cloud                                                 |   |                                                           |
| 6  | Zendar           | 2020 | Object Detection<br>Mapping<br>Localization                                                               | 2D box-level                   | Range-Doppler Tensor<br>Range-Azimuth Tensor<br>Point Cloud |    |                                                          |
| 7  | RADIATE          | 2020 | Object Detection<br>Object Tracking<br>SLAM<br>Scene Understanding                                        | 2D box-level                   | Range-Azimuth Tensor                                        |     |                                                         |
| 8  | AIODrive         | 2020 | Object Detection<br>Object Tracking<br>Semantic Segmentation<br>Trajectory Prediction<br>Depth Estimation | 2D box-level<br>3D box-level   | Point Cloud                                                 |      |                                                        |
| 9  | CRUW             | 2021 | Object Detection                                                                                          | 2D box-level                   | Range-Azimuth Tensor                                        |       |                                                       |
| 10 | RaDICaL          | 2021 | Object Detection                                                                                          | 2D box-level                   | ADC Signal                                                  |        |                                                      |
| 11 | RadarScenes | 2021 | Object Detection<br>Semantic Segmentation    | 2D pixel-level<br>3D point-level | Point Cloud                                                                                               | Mercedes-Benz AG, Stuttgart, Germany |   |
| 12 | RADDet      | 2021 | Object Detection                             | 2D box-level<br>3D box-level     | Range-Azimuth-Doppler Tensor                                                                              | University of Ottawa                 |   |
| 13 | FloW        | 2021 | Object Detection                             | 2D box-level                     | Range-Doppler Tensor<br>Point Cloud                                                                       | ORCA-Uboat                           |   |
| 14 | RADIal      | 2021 | Object Detection<br>Semantic Segmentation    | 2D box-level                     | ADC Signal<br>Range-Azimuth-Doppler Tensor<br>Range-Azimuth Tensor<br>Range-Doppler Tensor<br>Point Cloud | Valeo.ai, Paris, France              |   |
| 15 | VoD         | 2022 | Object Detection                             | 2D box-level<br>3D box-level     | Point Cloud                                                                                               | TU Delft, The Netherlands            |   |
| 16 | Boreas      | 2022 | Object Detection<br>Localization<br>Odometry | 2D box-level                     | Range-Azimuth Tensor                                                                                      | University of Toronto                |   |
| 17 | TJ4DRadSet  | 2022 | Object Detection<br>Object Tracking          | 3D box-level                     | Point Cloud                                                                                               | Tongji University                    |   |
| 18 | K-Radar     | 2022 | Object Detection<br>Object Tracking<br>SLAM  | 3D box-level                     | Range-Azimuth-Doppler Tensor                                                                              | KAIST                                |   |
| 19 | aiMotive    | 2022 | Object Detection                             | 3D box-level                     | Point cloud                                                                                               | aimotive                             |   |

## Datasets

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
