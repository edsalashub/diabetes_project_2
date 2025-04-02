# Diabetes Classification Project

Predicting diabetes using machine learning (Logistic Regression and KNN) on a dataset. This project includes data preprocessing, class imbalance handling, model training, and evaluation.

## Dataset
- **Source**: `diabetes_data.csv` (assumed to contain health-related features and a binary diabetes label).
- **Target Variable**: `Diabetes_binary`  0 = non-diabetic, 1 = diabetic
- **Class Distribution**: Imbalanced (resolved using oversampling).

## Dataset variables 

## Key Steps

### 1. Data Preprocessing
- **Handling Class Imbalance**: Used `RandomOverSampler` to balance the minority class.
- **Feature Scaling**: Applied `StandardScaler` to standardize features for KNN and Logistic Regression.

### 2. Model Training
- **Logistic Regression**: Model for binary classification.
- **K-Nearest Neighbors (KNN)**: Evaluated with `k` values from 1 to 19 (odd numbers only).

### 3. Evaluation
- Measured **accuracy** on training and testing data.
- Plotted accuracy vs. `k` for KNN to identify optimal performance.

## Results
- **Logistic Regression**:
  - Training Accuracy: 
  - Testing Accuracy: 
- **KNN**:
  - Best `k` Value: 


