# UASMachineLearning (Final Term) – Hands-on End-to-End Machine Learning & Deep Learning Projects


This repository contains a collection of **end-to-end Machine Learning and Deep Learning projects** developed as part of the **Final Term (UAS) Individual Task** for the Machine Learning course.

Each project demonstrates a complete pipeline, starting from data preprocessing, model development, training, evaluation, and result interpretation. The projects cover different problem types, including classification, regression, and image classification using neural networks.

**Learning Objectives**
- Design and implement end-to-end ML and DL pipelines
- Apply Neural Networks to tabular and image-based data
- Handle data preprocessing, feature scaling, and transformation
- Train and evaluate models using appropriate metrics
- Interpret and analyze model performance

**Project List**

**1. Fraud Detection (Classification – Tabular Data)**


**Repository:** `finalterm-ml-fraud-detection`


**Description:**  
This project focuses on predicting whether an online transaction is fraudulent using tabular transaction data. A **Feedforward Neural Network (MLPClassifier)** is implemented to learn non-linear patterns in the data.


**Key Techniques:**
- Data preprocessing with pipelines
- Handling missing values and feature scaling
- Neural Network classification (MLP)
- Evaluation using ROC-AUC

**2. Regression Modeling (Tabular Regression)**


**Repository:** `finalterm-ml-regression`


**Description:**  
This project implements an end-to-end regression pipeline to predict a continuous target value (e.g., song release year) from numerical features. A **Neural Network regression model (MLPRegressor)** is used to capture complex relationships in the data.


**Key Techniques:**
- Feature scaling
- Neural Network regression
- Evaluation using MSE, RMSE, MAE, and R²

**3. Image Classification (Deep Learning – CNN)**


**Repository:** `finalterm-dl-image-classification`


**Description:**  
This project builds a complete image classification pipeline using **Convolutional Neural Networks (CNN)**. Both a custom CNN and a transfer learning approach using **MobileNetV2** are implemented.


**Key Techniques:**
- Image preprocessing and augmentation
- CNN architecture design
- Transfer learning and fine-tuning
- Evaluation using accuracy, confusion matrix, and classification report

**Neural Network Implementation Summary**


Neural Networks are implemented across all projects:

- **Feedforward Neural Network (MLPClassifier)** for fraud detection
- **Feedforward Neural Network (MLPRegressor)** for regression
- **Convolutional Neural Networks (CNN)** for image classification

The Adam optimizer is used across Neural Network models, either explicitly or implicitly depending on the framework.

**Evaluation Metrics**


Different evaluation metrics are applied based on the task type:

- **Classification:** Accuracy, ROC-AUC, Confusion Matrix
- **Regression:** MSE, RMSE, MAE, R²
- **Image Classification:** Accuracy, Confusion Matrix, Classification Report

**Repository Navigation**


Each sub-repository contains:
- A Jupyter Notebook with code and explanations
- A dedicated README.md describing the project
- Dataset references and results


**Submission Notes**
- All projects are implemented as end-to-end pipelines
- Neural Networks are explicitly applied and documented
- Repositories are structured according to UAS submission guidelines

**Name:** Aisha Patricia Sekar Ayu



**NIM:** 1103223067
