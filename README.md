# Land Use Classification Using Satellite Imagery

This project focuses on land use classification using satellite imagery and deep learning techniques with TensorFlow and Keras.  
The project compares a custom CNN architecture with ResNet50 transfer learning for image classification.

---

## Project Overview

The model classifies satellite images into four categories:

- Cloudy
- Desert
- Green Area
- Water

Two deep learning approaches were implemented:

1. Custom CNN with residual blocks
2. ResNet50 transfer learning model

The pretrained ResNet50 model significantly improved classification accuracy compared to the baseline CNN model.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Scikit-learn
- PIL (Python Imaging Library)

---

## Deep Learning Techniques

### Custom CNN
- Convolutional layers
- Residual blocks
- Batch normalization
- Max pooling
- Dropout regularization
- Data augmentation

### Transfer Learning
- ResNet50 pretrained on ImageNet
- Frozen pretrained layers
- Global average pooling
- Dense classifier layers

---

## Optimization Techniques

- Early stopping
- Data augmentation
- Regularization
- Transfer learning

---

## Dataset

Satellite imagery dataset containing:

- Cloudy
- Desert
- Green Area
- Water

---

## Results

| Model | Best Validation Accuracy |
|---|---|
| Custom CNN | 91.30% |
| ResNet50 Transfer Learning | 99.91% |

---

## Model Comparison

The custom CNN achieved strong baseline performance using residual blocks and augmentation techniques.  
ResNet50 transfer learning significantly improved generalization and achieved near-perfect classification accuracy.

