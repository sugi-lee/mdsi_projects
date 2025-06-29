
## Introduction

This report outlines the implementation of pre-trained Convolutional Neural Networks (CNNs) to address multi-class image classification challenges. It covers model architecture, preprocessing techniques, activation functions, hyperparameter selection, training process, and evaluation metrics, demonstrating CNN effectiveness in image recognition.

### Background

CNNs are foundational in image recognition tasks. This project focuses on three pre-trained models:
- **GoogleNet**
- **MobileNet V3**
- **ResNet 50**

The training pipeline includes data augmentation, normalization, model selection, and loss function setup. We use the **Food-101** dataset from Data Vision to explore food image classification and deepen understanding of CNNs in real-world applications.

### Key Objectives

1. Apply **transfer learning** using GoogleNet, MobileNet V3, and ResNet 50.
2. **Fine-tune** the best-performing model based on initial experiments.

Each experiment involves tuning architectures and hyperparameters, with performance validated through robust evaluation. The ultimate goal is to balance **accuracy and generalization** for strong performance on unseen data.

## Dataset

This analysis uses a dataset from Data Vision containing 101 food categories, with 101,000 images total. Each category includes:

1. 250 manually reviewed test images
2. 750 training images (uncleaned, with some noise like intense colors or mislabeled data).
All images are resized to a maximum side length of 512 pixels.

### Data Preparation

Dataset is undergone data augmentation techniques by generating new variations of images to improve overfitting and improve generalisation.

| Transformation    | Explanation | Configuration |
|-------------------|-------------|---------------|
| RandomResizedCrop |


![Food Image Sample](./images/googlenet_pre.png)
