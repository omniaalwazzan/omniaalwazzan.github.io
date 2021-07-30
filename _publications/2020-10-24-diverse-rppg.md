---
title: "PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation"
collection: publications
permalink: /publication/2018-09-11-electron-ghost-imaging
excerpt: "Medical Image Segmentation."
date: 2012-08-04
venue: 'IEEE Access '
imageurl: '/images/publications/egi-thumb.png'
paperurl: '/files/electron-ghost-imaging.pdf'
link: 'https://doi.org/10.1109/ACCESS.2021.3071754'
citation: 'S. Li, F. Cropp, <strong>K. Kabra</strong>, Thomas J. Lane, G. Wetzstein, P. Musumeci, and D. Ratner (2018). &quot;PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation.&quot; <i> IEEE Access , 121</i>(11). doi:10.1109/ACCESS.2021.3071754'
---

## Abstract
A pyramidical multi-scale encoder-decoder network, namely PMED-Net, is proposed for medical image segmentation. Different variants of encoder-decoder networks are in practice for segmenting the medical images and U-Net is the most widely used one. However, the existing architectures for segmenting medical images have millions of parameters that require enormous computations which results in memory and cost-inefficiency. To overcome such limitations, we come up with the idea of training small networks in a cascaded form for coarse-to-fine prediction. The proposed adaptive network is extended up to six pyramid levels, and at each level, features are extracted at different scales of the input image. Each lightweight encoder-decoder network is trained independently to minimize loss, where succeeding level networks further refine the prior predictions. Evaluation and comparison of our architecture were performed on four different publicly available medical image segmentation datasets: International Skin Imaging Collaboration
(ISIC) challenge 2018 dataset, brain tumor dataset, nuclei dataset, and X-ray dataset. The experimental results of the PMED-Net are either better or on par with other state-of-the-art networks in terms of IoU, F1-Score, and sensitivity metrics. Moreover, PMED-Net is efficient in terms of parameterized complexity as it has 1/21.3, 1/21.1, 1/14.0, 1/11.6, 1/11.2, 1/6.64, and 1/4.95 times fewer parameters than SegNet, U-Net, BCDU-Net, CU-Net, FCN-8s, ORED-Net, and MultiResUNet respectively.

## Files
- [Paper](/files//files/PMED-Net.pdf)

## Citation
@inproceedings{chari2020-diverse-rppg,<br>
    title={PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation}, <br>
    author={A. Khan, H. Kim and L. Chua},<br>
    year={2021},<br>
}
