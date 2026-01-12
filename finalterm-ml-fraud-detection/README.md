**End-to-End Machine Learning Pipeline for Online Fraud Detection**

This repository contains an end-to-end machine learning pipeline developed to predict the probability of an online transaction being fraudulent. The project covers the complete workflow starting from data preprocessing to model evaluation using tabular transaction and identity data.

The main objective of this project is to apply machine learning techniques to a real-world fraud detection problem and evaluate the model’s ability to generalize to unseen data.

**Objectives**
- Perform data cleaning and preprocessing on transaction data
- Handle missing values and class imbalance
- Train and evaluate machine learning models for fraud detection
- Analyze model performance using appropriate classification metrics

**Dataset Description**
The dataset consists of transaction records with a binary target variable `isFraud`:
- **train_transaction.csv**: Labeled transaction data used for training and evaluation
- **test_transaction.csv**: Unlabeled transaction data used for prediction

Each transaction is described by multiple numerical and categorical features such as transaction amount, product code, card information, and address-related attributes.

**Workflow**
1. Data loading and exploration
2. Handling missing values
3. Encoding categorical features
4. Handling class imbalance
5. Model training
6. Model evaluation using classification metrics
7. Performance analysis

**Models Used**
- Machine Learning classification model (e.g., LightGBM / Logistic Regression)
- Feedforward Neural Network

The Neural Network model consists of multiple fully connected layers trained to learn non-linear patterns in transaction data

**Neural Network Architecture**
The Neural Network model is built using a feedforward architecture with:
- Input layer corresponding to the feature size
- Hidden layers with ReLU activation
- Output layer with sigmoid activation for binary classification

The model is trained using binary cross-entropy loss and optimized using Adam optimizer

**Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

**Repository Structure**
fraud_transaction.ipynb
README.md

