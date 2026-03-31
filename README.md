# Beyond Prediction: Comparing ML Workflows for House Price Prediction
> A comparative end-to-end machine learning project focusing on workflow design, data understanding and interpretable modeling.

This project presents an end-to-end machine learning workflow for predicting house prices based on the Ames Housing dataset.
Unlike standard approaches that focus solely on model performance, this project compares different **machine learning workflows** and demonstrates how preprocessing strategy, feature design and data understanding influence both predictive accuracy and interpretability.

The project is designed as a portfolio piece to highlight structured analytical thinking, reproducible pipelines and explainable machine learning.

---

## Project Overview

The core objective is not only to predict house prices, but to understand how different approaches to the same problem affect results.

Three workflows are implemented and compared:

- **Manual workflow**  
  Step-by-step preprocessing and modeling with explicit, human-driven decisions.

- **Blind pipeline-based workflow**  
  A standardized machine learning pipeline following general best practices without incorporating dataset-specific insights.

- **Insight-driven pipeline**  
  A reproducible pipeline that integrates findings from exploratory data analysis and domain understanding.

---

## Key Objectives

- perform structured data cleaning and preprocessing  
- analyze and handle missing values (including structural missingness)  
- engineer meaningful and interpretable features  
- train and evaluate multiple regression models  
- compare different machine learning workflows  
- extract interpretable decision rules from a simplified model  

---

## Dataset

The project uses the **Ames Housing dataset**, a well-known benchmark dataset for regression problems in machine learning.

It contains detailed information about residential homes, including:

- property characteristics  
- quality indicators  
- location-based features  
- structural attributes  

---

## Models Used

The following models were trained and evaluated:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  

Model performance was evaluated using:

- Root Mean Squared Error (RMSE)  
- R² score  
- Cross-validation  

---

## Workflow Comparison

### 1. Manual Workflow

A fully transparent, step-by-step approach including:

- targeted missing value handling  
- domain-informed encoding strategies  
- manual feature engineering  
- explicit feature selection  

This approach prioritizes **understanding and control** over automation.

---

### 2. Blind Pipeline

A generic pipeline using standard techniques:

- automated imputation  
- one-hot encoding  
- scikit-learn pipeline structure  

This represents a **purely technical best-practice baseline**, without incorporating insights from the data exploration phase.

---

### 3. Insight-Driven Pipeline

A refined pipeline that combines:

- reproducibility of pipelines  
- insights from exploratory data analysis  
- improved feature representation  

This approach aims to balance **performance, interpretability, and robustness**.

---

## Interpretability

To complement high-performing models, a simplified decision tree was used to extract **interpretable decision rules**.

Continuous house prices were transformed into categories (*Very Low*, *Low*, *Medium*, *High*) to improve readability.

These rules provide:

- intuitive understanding of key drivers  
- transparent decision logic  
- explainable approximations of complex models  

---

## Key Insights

- Model performance depends not only on the algorithm, but heavily on preprocessing and feature engineering  
- Domain understanding significantly improves model quality  
- Pipelines increase reproducibility but may underperform if applied blindly  
- There is a clear trade-off between **predictive performance** and **interpretability**  


