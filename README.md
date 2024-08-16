

# Face Mask Detection Model

This repository contains a Convolutional Neural Network (CNN) model designed for detecting face masks using the [Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset) from Kaggle. The model achieves an accuracy of 92.89% in classifying whether individuals are wearing a mask or not.

## Table of Contents

- [Introduction](#introduction)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Training](#training)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction

This project aims to build a reliable face mask detection system utilizing deep learning techniques. The trained model can be employed in real-time applications to ensure mask compliance and enhance safety measures.

## Model Architecture

The model is based on a Convolutional Neural Network (CNN) and is designed to classify images into two categories:

1. **With Mask**
2. **Without Mask**

### Key Features

- **Optimizer**: Adam Optimizer
- **Loss Function**: Sparse Categorical Cross Entropy
- **Accuracy**: 92.89%

## Dataset

The model is trained using the [Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset), which consists of images categorized into two classes:

- **With Mask**: Images of people wearing face masks.
- **Without Mask**: Images of people not wearing face masks.

## Training

The model was trained with the following parameters:

- **Batch Size**: 149
- **Epochs**: 50
- **Learning Rate**: 0.001

## Evaluation

The model's performance was evaluated using accuracy metrics. The achieved accuracy is 92.89%, indicating a high level of precision in detecting face masks.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
