# RL-Assisted SAM Segmentation in Diverse Medical Imaging Modalities
Code for the paper [Bridging the Gap in Lesion Segmentation: RL-Assisted SAM Segmentation in Diverse Medical Imaging Modalities]

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

## Pre-trained and Fine-tuned Models
To download the trained pre-trained models for RL: [Google Drive][https://drive.google.com/file/d/15_3dhBL4HmU-U5f3-vJp2lfTFBnTIKLu/view?usp=drive_link]

To download the trained fine-tuned models for SAM_RL:

