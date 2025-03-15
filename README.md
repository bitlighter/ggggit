
# STAD-Clip

## Overview
This repository contains the code for STAD-Clip: Side-Branch Spatiotemporal Enhancement with CLIP for Zero-/Few-shot Traffic Anomaly Detection [paper](https://www.baidu.com/)

##  Installation
-   Recommended Environment: python >= 3.10, cuda 12.2, PyTorch 2.0.1
-   Install dependencies:  `pip install -r requirements.txt` 

## Data Preparation

Download DoTA dataset from [DoTA](https://github.com/MoonBlvd/Detection-of-Traffic-Anomaly)

Download DADA dataset from [DADA](https://github.com/JWFangit/LOTVS-DADA)

Modify the path of dataset in `main.py` and `dataset/datasets_list.py`

## Pre-trained Models
-   [**Pre-trained STAD-Clip Models**](https://drive.google.com/drive/folders/1zv_1h8zBocywhU5fsPeKtbxTp7xlMZYL?usp=sharing): You can also download and use the pre-trained weights of STAD-Clip. The pretrained model weights are intended for testing and demo purposes. To utilize the pre-trained model for testing, please download it and ensure it is placed in the appropriate directory.

## Training and Testing
#### Run Training  on DoTA dataset
`./scripts/train.sh`

#### Run Testing  on DoTA dataset
`./scripts/eval_DoTA.sh`

#### Run Testing  on DADA dataset
`./scripts/eval_DADA.sh`

## Citation
```
@InProceedings{Du_2024_CVPR,
    author    = {Du, Yunhao and Lei, Cheng and Zhao, Zhicheng and Su, Fei},
    title     = {iKUN: Speak to Trackers without Retraining},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2024},
    pages     = {19135-19144}
}
```



