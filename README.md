# CP dataset
[![website](https://img.shields.io/badge/Website-Explore%20Now-blueviolet?style=flat&logo=google-chrome)](https://catslab.engr.wisc.edu/)
[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://catslab.engr.wisc.edu/)
[![video](https://img.shields.io/badge/Video-Presentation-F9D371)](https://catslab.engr.wisc.edu/)

Supported by the [University of Wisconisn Madison CATS Lab](https://catslab.engr.wisc.edu/).
The data collection equipments of CATS Lab are as follow:
<p align="center">
<img src="img/equip.jpeg" width="600" alt="" class="img-responsive">
</p>

Demo data can be provided as the following: 
<p align="center">
<img src="img/data.jpeg" width="600" alt="" class="img-responsive">
</p>


## Overview
- [CP dataset](#cp-dataset)
  - [Overview](#overview)
  - [CodeBase Features](#codebase-features)
  - [Data Collection Pipeline](#data-collection-pipeline)
  - [Data Download](#data-download)
  - [Changelog](#changelog)
  - [Devkit setup](#devkit-setup)
      - [1. Create conda environment (python \>= 3.7)](#1-create-conda-environment-python--37)
      - [2. Pytorch Installation (\>= 1.12.0 Required)](#2-pytorch-installation--1120-required)
      - [3. Install other dependencies](#3-install-other-dependencies)
  - [Quick Start](#quick-start)
    - [Data sequence visualization](#data-sequence-visualization)
  - [Citation](#citation)
  - [Acknowledgment](#acknowledgment)

## CodeBase Features
- Multiple Weather conditions supported
    - [x] Cloudy
    - [x] Sunny
    - [x] Foggy
    - [x] Snowy
    - [ ] ......
- Multiple Tasks supported
    - [x] 3D cooperative object detection
    - [x] Cooperative tracking
    - [x] Domain adaptation
    - [x] ....
- SOTA model supported
    - [x] ...
    - [ ] Prof.Yu's work can be added to this dataset framework
## Data Collection Pipeline
To be added

## Data Download
Please check our [website](https://catslab.engr.wisc.edu/) to download the data.

After downloading the data, please put the data in the following structure:
```shell
├── CP_dataset
│   ├── train
|      |── scenerio 1
│   ├── validate
│   ├── test
```
## Changelog
- Oct. 7, 2024: Tha intital commit to this repo

## Devkit setup
Need to be set. Basically steps are as follow:

To set up the codebase environment, do the following steps:
#### 1. Create conda environment (python >= 3.7)
```shell
conda create -n CP python=3.7
conda activate CP
```
#### 2. Pytorch Installation (>= 1.12.0 Required)
Take pytorch 1.12.0 as an example:
```shell
conda install pytorch==1.12.0 torchvision==0.13.0 cudatoolkit=11.3 -c pytorch -c conda-forge
```
#### 3. Install other dependencies
```shell
pip install -r requirements.txt
python setup.py develop
```

## Quick Start
### Data sequence visualization



## Citation
```shell
@inproceedings{CP,
  title={CP},
  author={Xiaopeng Li},
  booktitle={The IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR)},
  year={2024}
}
```

## Acknowledgment
This dataset is supported by XXX funding, the data is collected from U-Wisconsin Milwakee. ....