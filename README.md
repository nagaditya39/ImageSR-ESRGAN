---
# ESRGAN (Enhanced Super-Resolution Generative Adversarial Network)

ESRGAN is a deep learning-based model designed for image super-resolution tasks. It enhances the resolution of low-resolution images, generating high-quality and realistic high-resolution images.

## Overview

This repository contains the implementation of an ESRGAN model using PyTorch. The model architecture consists of a generator and a discriminator trained in an adversarial manner.

## Features

- Utilizes a Generative Adversarial Network (GAN) architecture for super-resolution tasks.
- Incorporates Residual in Residual Dense Blocks (RRDB) for effective feature extraction and learning.
- Implements a custom loss function, including perceptual loss (VGG loss) and adversarial loss.
- Provides data preprocessing utilities using Albumentations library.
- Supports training and inference functionalities for image super-resolution.

## Requirements

- Python 3.x
- PyTorch
- Albumentations
- OpenCV
- NumPy
- tqdm
- PIL (Python Imaging Library)

## Usage

1. Clone this repo.

```
git clone https://github.com/nagaditya39/ImageSR-ESRGAN.git
cd ImageSR-ESRGAN
```
2. Prepare low-resolution images for inference, in the folder labelled  `test_images`
3. Run the `train.py` script to start training the ESRGAN model.
4. The high-resolutions images will be generated and stored in the folder `saved`
### Example



## Results
<p align="center">
  <img src="figures/qualitative_cmp_01.jpg">
</p>
<p align="center">
  <img src="figures/qualitative_cmp_02.jpg">
</p>

## Acknowledgments

- This project is inspired by the original ESRGAN paper: [ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks](https://arxiv.org/abs/1809.00219).
- This project derives inspiration from the original ESRGAN Implementation: [https://github.com/xinntao/ESRGAN]
- Special thanks to the PyTorch community for their contributions to deep learning research and development.

---
