# Fruits Recognition Using Deep Learning with Data Augmentation

A deep learning project for classifying fruit images using CNNs, custom data augmentation, and transfer learning. Built on the [Fruits-360 dataset](https://www.kaggle.com/datasets/moltean/fruits), this project focuses on improving robustness with background replacement, noise, blur, and attention mechanisms.

## Overview

Trained and evaluated the following models:

- **EfficientNetB0**
- **ResNet50**
- **MobileNetV2**

## Dataset

- **Fruits-360**: 130+ fruit classes with uniform backgrounds
- All images resized to **100x100**
- Split into training, validation, and test sets

## Key Features

- Transfer Learning using pretrained CNNs
- Background replacement with random textures to simulate real-world conditions
- Extra augmentations: blur, noise, flips, zoom
- SE block to enhance channel-wise attention
- Early stopping and model checkpointing
- Detailed evaluation: classification reports, confusion matrices

## Training Process
![Image](https://github.com/user-attachments/assets/4ccc9cb3-c13c-4d97-8c9c-b5386218e590)
