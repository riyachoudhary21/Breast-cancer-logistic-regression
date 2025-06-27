# Breast-cancer-logistic-regression


## Overview  
This repository contains a logistic regression-based binary classifier applied to the **Breast Cancer Wisconsin Diagnostic dataset**. It demonstrates a full machine learning workflow—from data preprocessing to model evaluation and sigmoid interpretation.


## Objectives  
- Clean and preprocess the dataset.  
- Build a logistic regression model.  
- Evaluate the model using key metrics.  
- Explore threshold tuning and sigmoid function behavior.  


## Tools & Technologies  
- **Language**: Python  
- **Environment**: Google Colab  
- **Libraries**:  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – ML modeling and metrics  
  - `scipy.special` – Sigmoid (logistic) function   


## Workflow & Highlights  

### 1. Data Preprocessing  
- Dropped empty columns/rows  
- Converted diagnosis to binary (M=1, B=0)  
- Standardized features using `StandardScaler`  

### 2. Model Building  
- Applied Logistic Regression with `max_iter=1000`  
- Performed an 80-20 train-test split with stratification  

### 3. Evaluation Metrics  
- **Confusion Matrix**  
- **Classification Report** (Precision, Recall, F1-score)  
- **ROC Curve** with **AUC = 0.99**  

### 4. Advanced Analysis  
- Threshold tuning to adjust sensitivity/specificity  
- Visualization of the **Sigmoid function**  


## Visual Outputs  
- Confusion Matrix (Default & Custom Threshold)  
- ROC Curve  
- Sigmoid Function Plot  


## Key Insights  
- Achieved **~95% accuracy** and **0.99 AUC**.  
- Radius, texture, and perimeter are significant features.  
- Lowering threshold improves recall, but may reduce precision.  


## Learning Outcomes  
- Hands-on experience with logistic regression.  
- Deep understanding of classification evaluation.  
- Insight into sigmoid probability output and thresholding.  
