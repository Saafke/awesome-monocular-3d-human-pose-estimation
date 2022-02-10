# Monocular 3D human pose estimation
One stop shop for everything related to 3D human pose estimation from a single RGB image or video.

Please feel free to make pull requests so we can keep this repository as complete and up-to-date as possible.

## Table of Contents
- [Getting Started](#start)
- [Human Body Models](#bodymodels)
- [Monocular Estimation Models](#estimation)
  - [Predicting only 3D joints](#joints)
  - [Predicting 3D meshes](#meshes)
- [Datasets](#datasets)


&nbsp;
&nbsp;
## Getting Started <a name="start"></a>
Here are some good resources to get started on studying this subfield of computer vision. 

<details>
  <summary>Survey papers</summary>
  
  - [Monocular Human Pose Estimation: A Survey of Deep Learning-based Methods](https://arxiv.org/abs/2006.01423)
  - [A survey on monocular 3D human pose estimation](https://www.sciencedirect.com/science/article/pii/S2096579620300887)
  - [Deep 3D human pose estimation: A review](https://www.sciencedirect.com/science/article/pii/S1077314221000692)
  
  
</details>
  
<details>
  <summary>Other</summary>
  
  - [OpenPose GitHub](https://github.com/CMU-Perceptual-Computing-Lab/openpose)
  - https://paperswithcode.com/task/monocular-3d-human-pose-estimation 
  - [SMPL paper](https://files.is.tue.mpg.de/black/papers/SMPL2015.pdf)
  - [ArXiv feed](https://arxiv.org/search/?query=3D+human+pose&searchtype=all&source=header)
  
</details>


&nbsp;
&nbsp;
## 3D Human Body Models <a name="bodymodels"></a>
<details>
  <summary>Details</summary>
  
  | Model name   | Year | Description                                          | Link |
  | :---         | :----|    :----                                             |          ---: |
  | SCAPE        | 2005 | Shape Completion and Animation of People | [[Project page]](http://ai.stanford.edu/~drago/Projects/scape/scape.html) |
  | BlendSCAPE   | 2012 | Coregistration: Simultaneous Alignment and Modeling of Articulated 3D Shape | [[Paper PDF]](https://files.is.tue.mpg.de/black/papers/HirshbergECCV2012.pdf) |
  | SMPL         | 2015 | A Skinned Multi-Person Linear Model                  | [[Project page]](https://smpl.is.tue.mpg.de/)      |
  | SMPL-X       | 2019 | SMPL eXpressive                                      | [[Project page]](https://smpl-x.is.tue.mpg.de/)    |
  | STAR         | 2020 | A Sparse Trained Articulated Human Body Regressor    | [[Project page]](https://star.is.tue.mpg.de/)      |
  | GHUM & GHUML | 2020 | Generative 3D Human Shape and Articulated Pose Models| [[GitHub page]](https://github.com/google-research/google-research/tree/master/ghum)|

</details>


&nbsp;
&nbsp;
## Monocular Estimation models <a name="estimation"></a>

### 3D Joints <a name="joints"></a>
Methods that estimate from a single RGB image or video a human skeleton consisting of 3D joints.

<details>
  <summary>Details</summary>

  | Model name   | Year | Description                                                | Temporal | Link |
  | :---         | :----|    :----                                                   |:---:|     ---: |
  | - | - | - | - | - |
  
</details>


&nbsp;
### 3D Mesh <a name="meshes"></a>
Methods that estimate from a single RGB image or video the whole 3D human body mesh.
  
<details>
  <summary>Details</summary>
 
  | Model name   | Year | Description                                                | Body model used | Temporal | Link |
  | :---         | :----|    :----                                                   | :---:           |:---:|     ---: |
  | DecoMR       | 2020 | 3D Human Mesh Regression with Dense Correspondence         | SMPL | :white_large_square: | [[GitHub page]](https://github.com/zengwang430521/DecoMR)
  | VIBE         | 2020 | Video Inference for Human Body Pose and Shape Estimation   | SMPL        |:white_check_mark:  |[[GitHub page]](https://github.com/mkocabas/VIBE)|
  | -            | 2021 | Human Performance Capture from Monocular Video in the Wild | SMPL            |:white_check_mark:  |  [[PDF]](https://arxiv.org/pdf/2111.14672.pdf)|

</details>


&nbsp;
&nbsp;
## Datasets <a name="datasets"></a>
All the related datasets for this task. Quickly from memory: AGORA, AMASS, 3DPW, 3.6Human, 
<details>
  <summary>Details</summary>
  
  | Name   | Year | Description | Size     | Link |
  | :---   | :----| :----       |:---:     | ---: |
  | 3DPW   | 2018 | 3D poses in the wild   | - | [[Project page]](https://virtualhumans.mpi-inf.mpg.de/3DPW/) |

</details>


