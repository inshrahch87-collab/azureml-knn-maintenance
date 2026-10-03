# azureml-knn-maintenance
# Azure Machine Learning Lab - Predictive Maintenance

## Overview
This project demonstrates end-to-end workflow execution in Azure ML Studio, including data preparation, training a custom KNN model, running Automated ML (AutoML), evaluating model performance, and managing cloud resources efficiently.

---

## Lab Documentation & Screenshots

### 1. Data Asset Creation
Data registered as `ai4i-maintenance-table`.
![Data Asset](screenshots/screenshot-1.png)

### 2. Data Preparation & Cleaning
Data preprocessing and missing values handling in Azure ML Notebooks.
![Data Prep](screenshots/screenshot-2.png)

### 3. Custom KNN Model Training
Training a K-Nearest Neighbors classifier on cleaned data.
![Custom KNN](screenshots/screenshot-3.png)

### 4. AutoML Configuration
Setting up AutoML experiment with target variable `Machine failure`.
![AutoML Config](screenshots/screenshot-4.png)

### 5. AutoML Running Status
AutoML job initialization and execution status.
![AutoML Running](screenshots/screenshot-5.png)

### 6. AutoML Experiment Overview
Job summary showing completed experiment status.
![AutoML Overview](screenshots/screenshot-6.png)

### 7. Child Jobs & Models List
List of models evaluated by AutoML. Best performing model: `StandardScalerWrapper, XGBoostClassifier` (AUC: 0.976).
![Models List](screenshots/screenshot-7.png)

### 8. Best Model Performance Metrics
Metrics view for the best model showing Accuracy (0.984) and ROC / Confusion Matrix charts.
![Best Model Metrics](screenshots/screenshot-8.png)

### 9. Resource Management (Compute Shutdown)
Stopping compute instance `ci-inshraheyman14` to prevent unnecessary credit consumption.
![Compute Shutdown](screenshots/screenshot-9.png)

---

## Results & Best Model Performance
- **Best Model:** `StandardScalerWrapper, XGBoostClassifier`
- **AUC Weighted:** `0.976`
- **Accuracy:** `0.984`
