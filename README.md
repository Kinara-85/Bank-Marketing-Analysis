# Bank Marketing Campaign Analysis

## Project Overview
This project analyzes a bank's marketing campaign dataset to determine factors influencing customer subscription to term deposits. It involves data preprocessing, feature engineering, model training, and evaluation.

This project was completed as part of a **PwC Virtual Internship**.

## Dataset
The dataset contains customer details, marketing interactions, and economic indicators. The target variable is whether a customer subscribed to a term deposit.
Data is from UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/222/bank+marketing

## Process Flowchart
```plaintext
Start
  |
  v
Read Dataset  -->  Data Cleaning  -->  Handling Missing Values  -->  Removing Duplicates
  |
  v
Handling Outliers  -->  Feature Engineering (Encoding, Scaling, Transformation)
  |
  v
Splitting Dataset (Train/Test)  -->  Data Analysis (Correlation, PCA)
  |
  v
Model Training (SVM)  -->  Model Evaluation (Accuracy, Confusion Matrix, Precision, Recall, F1 Score)
  |
  v
SMOTE for Balancing Data  -->  Retrain Model  -->  Final Evaluation
  |
  v
End
```

## Steps Involved

### 1. Data Preparation
- Load dataset
- Drop unnecessary columns
- Handle missing values
- Remove duplicate entries

### 2. Handling Outliers
- Visualize outliers using boxplots and histograms
- Remove extreme values

### 3. Feature Engineering
- Encode categorical variables
- Apply transformations (log, exponential)
- Scale numerical features

### 4. Data Analysis
- Compute correlation matrix
- Perform Principal Component Analysis (PCA)

### 5. Model Training
- Train a Support Vector Machine (SVM) classifier
- Evaluate model using accuracy, confusion matrix, precision, recall, and F1-score

### 6. Model Improvement
- Apply SMOTE to balance the dataset
- Retrain the model and assess performance

## Technologies Used
- Python (pandas, numpy, seaborn, matplotlib, sklearn, imblearn)

## Results
- Identified key features affecting customer decisions
- Improved model performance with SMOTE
- Achieved optimized accuracy using SVM

## Author
**Faiza Bashir** - PwC Virtual Internship Project

---
🚀


