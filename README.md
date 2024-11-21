# RL-Assisted SAM Segmentation in Diverse1 Medical Imaging Modalities
Code for the paper [Bridging the Gap in Lesion Segmentation: RL-Assisted SAM Segmentation in Diverse Medical Imaging Modalities ()]

## Dependencies 
- python 3.6.5
- numpy 1.14.5
- scipy 1.1.0
- Pytorch 0.4.0

## Scripts
The folder 'scripts' contains the different bash scripts that could be used to train the same models used in the paper, for both Camvid and Cityscapes datasets. 
- launch_baseline.sh: To train the baselines 'random'.
- launch_train_ralis.sh: To train the 'SAM RL agent' model.
- launch_test_ralis.sh: To test the 'SAM RL agent' model. 

## Datasets
Camvid: https://github.com/alexgkendall/SegNet-Tutorial/tree/master/CamVid

Cityscapes: https://www.cityscapes-dataset.com/

## Trained models
To download the trained RALIS models for Camvid and Cityscapes (as well as the pretrained segmentation model on GTA and D_T subsets): https://drive.google.com/file/d/13C4e0bWw6SEjTAD7JdAfLGVz7p7Veeb9/view?usp=sharing
## Citation
If you use this code, please cite:
```
@inproceedings{
Casanova2020Reinforced,
title={Reinforced active learning for image segmentation},
author={Arantxa Casanova and Pedro O. Pinheiro and Negar Rostamzadeh and Christopher J. Pal},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=SkgC6TNFvr}
}
```
