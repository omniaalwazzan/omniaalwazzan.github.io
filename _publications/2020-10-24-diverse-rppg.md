---
title: "PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation"
collection: publications
permalink: /publication/2020-10-24-diverse-rppg
date: 2021-04-16
imageurl: '/images/publications/PMED.PNG'
paperurl: '/files/Diverse-RPPG.pdf'
link: 'https://ieeexplore.ieee.org/document/9399071'
citation: 'A. Khan, H. Kim and L. Chua, "PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical
Image Segmentation," in IEEE Access, doi: 10.1109/ACCESS.2021.3071754'
---

Pradyumna Chari<sup>1</sup>, <strong>Krish Kabra<sup>1</sup></strong>, Doruk Karinca<sup>1</sup>, Soumyarup Lahiri<sup>1</sup>, Diplav Srivastava<sup>1</sup>, Kimaya Kulkarni<sup>1</sup>, Tianyuan Chen<sup>1</sup>, Maxime Cannesson<sup>2</sup>, Laleh Jalilian<sup>2</sup>, Achuta Kadambi<sup>1,3,*</sup>

<sup>1</sup>Department of Electrical and Computer Engineering, UCLA, Los Angeles, California 90095, USA<br>
<sup>2</sup>Department of Anesthesiology and Perioperative Medicine, UCLA, Los Angeles, California 90095, USA<br>
<sup>3</sup>California NanoSystems Institute, University of California, Los Angeles, California 90095, USA<br>
<sup>*</sup>Corresponding author: achuta@ee.ucla.edu<br>

<center><img src = '/images/publications/diverse-rppg-video-demo.gif'></center>

<i>The proposed method uses small variations in skin color, as well as novel physics guided techniques to estimate the heart rate in a skin tone robust manner. 
The plots show low pass filtered versions (containing the first and second harmonics of the estimated pulse rate) of both the ground truth and estimated pulse 
waveforms to visualize the similarity.</i>

## Abstract
A pyramidical multi-scale encoder-decoder network, namely PMED-Net, is proposed for medical image segmentation. Different variants of encoder-decoder networks are in practice for segmenting the medical images and U-Net is the most widely used one. However, the existing architectures for segmenting medical images have millions of parameters that require enormous computations which results in memory and cost-inefficiency. To overcome such limitations, we come up with the idea of training small networks in a cascaded form for coarse-to-fine prediction. The proposed adaptive network is extended up to six pyramid levels, and at each level, features are extracted at different scales of the input image. Each lightweight encoder-decoder network is trained independently to minimize loss, where succeeding level networks further refine the prior predictions. Evaluation and comparison of our architecture were performed on four different publicly available medical image segmentation datasets: International Skin Imaging Collaboration
(ISIC) challenge 2018 dataset, brain tumor dataset, nuclei dataset, and X-ray dataset. The experimental results of the PMED-Net are either better or on par with other state-of-the-art networks in terms of IoU, F1-Score, and sensitivity metrics. Moreover, PMED-Net is efficient in terms of parameterized complexity as it has 1/21.3, 1/21.1, 1/14.0, 1/11.6, 1/11.2, 1/6.64, and 1/4.95 times fewer parameters than SegNet, U-Net, BCDU-Net, CU-Net, FCN-8s, ORED-Net, and MultiResUNet respectively.

## Files
- [Paper](/files//files/Diverse-RPPG.pdf)

## Citation
@inproceedings{chari2020-diverse-rppg,<br>
    title={PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation}, <br>
    author={A. Khan, H. Kim and L. Chua},<br>
    year={2021},<br>
}
