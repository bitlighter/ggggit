
# STAD-Clip: Side-Branch Spatiotemporal Enhancement with CLIP for Zero-/Few-shot Traffic Anomaly Detection

## Overview
This repository contains the code for STAD-Clip: Side-Branch Spatiotemporal Enhancement with CLIP for Zero-/Few-shot Traffic Anomaly Detection [paper](https://www.baidu.com/)

##  Installation
-   Recommended Environment: python >= 3.10, cuda 12.2, PyTorch 2.0.1
-   Install dependencies:  `pip install -r requirements.txt` 
- 
## Data Preparation

Download DoTA from [DoTA](https://github.com/happyharrycn/actionformer_release/tree/main)

Download DADA from [DADA](https://github.com/happyharrycn/actionformer_release/tree/main)

Modify the path of dataset in main.py and dataset/datasets_list.py

## Pre-trained Models
-   [**Pre-trained AM-Net Models**](https://drive.google.com/drive/folders/1zv_1h8zBocywhU5fsPeKtbxTp7xlMZYL?usp=sharing): You can also download and use the pre-trained weights of AM-Net. The pretrained model weights are intended for testing and demo purposes. To utilize the pre-trained model for testing, please download it and ensure it is placed in the appropriate directory.

## Training and Testing
#### Run Training  on DoTA dataset
`./scripts/train.sh`

#### Run Testing  on DoTA dataset
`./scripts/eval.sh`

#### Run Testing  on DADA dataset
`./scripts/eval.sh`



