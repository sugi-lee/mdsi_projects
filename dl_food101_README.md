
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
