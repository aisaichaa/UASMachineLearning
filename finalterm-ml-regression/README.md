**End-to-End Regression Modeling Using Neural Network**


This repository implements an end-to-end regression pipeline to predict a continuous target value from numerical input features. In this project, a **Neural Network regression model** is used to learn non-linear relationships between input features and the target variable.

The project demonstrates the complete machine learning workflow, including data preprocessing, model training, evaluation, and interpretation of results.

**Objectives**
- Build an end-to-end regression pipeline
- Perform data preprocessing and feature scaling
- Train a Neural Network model for regression tasks
- Evaluate model performance using appropriate regression metrics
- Interpret regression results

**Dataset Description**
- **midterm-regresi-dataset.csv**

The dataset consists of:
- A continuous target variable (e.g., song release year)
- Multiple numerical input features representing audio characteristics

All features are numerical and require proper scaling before model training.

**Workflow**
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Feature scaling using standardization
4. Model training
5. Model evaluation
6. Result interpretation

**Neural Network Regression Model**
This project uses a **Feedforward Neural Network** for regression implemented using `MLPRegressor` from **scikit-learn**.

**Model Characteristics:**
- Architecture: Multi-Layer Perceptron (MLP)
- Hidden layers with ReLU activation
- Output layer with a single neuron for continuous value prediction
- Optimizer: **Adam** (default solver in `MLPRegressor`)
- Loss function: Mean Squared Error (MSE)

The Adam optimizer is used implicitly via the default `solver='adam'`, enabling efficient optimization for regression tasks with high-dimensional numerical data.

**Model Implementation**
The regression model is trained using a preprocessing pipeline that includes:
- Feature scaling with `StandardScaler`
- Neural Network regression model (`MLPRegressor`)

The preprocessing and modeling steps are combined into a single scikit-learn `Pipeline` to ensure reproducibility and clean separation of concerns.

**Evaluation Metrics**
The regression model is evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

These metrics provide a comprehensive assessment of prediction accuracy and model fit.

**Repository Structure**
- Regresi_Dataset.ipynb
- README.md


**Nama:** Aisha Patricia Sekar Ayu


**NIM:** 1103223067

