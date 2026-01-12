**End-to-End Image Classification Using Convolutional Neural Networks (CNN)**


This repository implements an end-to-end image classification pipeline using **Convolutional Neural Networks (CNN)**. The project focuses on classifying fish images into multiple classes using both a custom CNN model and a transfer learning approach.

The complete workflow includes image preprocessing, data augmentation, model training, evaluation, and result interpretation.

**Objectives**
- Build an end-to-end image classification pipeline
- Apply image preprocessing and data augmentation techniques
- Design and train CNN-based models
- Apply transfer learning using a pre-trained deep neural network
- Evaluate model performance using appropriate classification metrics

**Dataset Description**
- **Fish Image Dataset**

The dataset consists of images from multiple fish species. Each image belongs to a single class representing a fish category. The dataset is split into training, validation, and testing sets.

**Workflow**
1. Image loading and preprocessing
2. Data augmentation for training images
3. Dataset splitting (train, validation, test)
4. Model building
5. Model training
6. Model evaluation
7. Performance analysis and visualization

**Convolutional Neural Network Models**

**1. Custom CNN**
A CNN model built from scratch using convolutional and pooling layers to automatically extract spatial features from images.

**Model characteristics:**
- Convolutional layers for feature extraction
- Pooling layers for dimensionality reduction
- Fully connected layers for classification
- Softmax output layer for multi-class classification

**2. Transfer Learning (MobileNetV2)**
A deep CNN model based on **MobileNetV2**, pre-trained on the ImageNet dataset, is used to improve performance and training efficiency.

**Model characteristics:**
- Pre-trained MobileNetV2 as feature extractor
- Fine-tuning on the fish image dataset
- Optimizer: **Adam**
- Loss function: Categorical Cross-Entropy

**Model Implementation**
The CNN models are implemented using **TensorFlow / Keras**. Image preprocessing and augmentation are applied using `ImageDataGenerator` to improve generalization and reduce overfitting.

**Evaluation Metrics**
Model performance is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report

These metrics are used to assess classification performance across all classes.

**Repository Structure**
- CNN_end_to_end.ipynb
- README.md


**Nama:** Aisha Patricia Sekar Ayu


**NIM:** 1103223067

