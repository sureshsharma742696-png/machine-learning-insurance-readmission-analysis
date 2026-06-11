# machine-learning-insurance-readmission-analysis
Insurance Cost Prediction and Patient Readmission Analysis using Scikit-Learn, Linear Regression and Logistic Regression.

This repository contains an end-to-end Machine Learning project that addresses two distinct real-world problems in the healthcare and insurance sectors: Regression for Cost Prediction and Classification for Patient Readmission.

## Project Overview

### 1. Insurance Cost Prediction (Regression)
Objective: Predict the yearly medical charges for new customers based on demographic and health indicators.
Model Used: Linear Regression
Key Insights: Identified primary cost drivers, highlighting how heavily lifestyle habits like smoking impact overall medical expenses.

### 2. Patient Readmission Analysis (Classification)
Objective: Predict whether a hospital patient is at high risk of being readmitted within 30 days.
Model Used: Logistic Regression
Business Strategy: Adjusted the default decision threshold above 0.5 to achieve higher Precision, effectively creating a highly reliable high-risk watch list while minimizing false alarms.

## Tech Stack and Libraries
Language: Python
Data Libraries: Pandas, NumPy
Machine Learning: Scikit-Learn
Visualization: Matplotlib, Seaborn

## Key Steps Performed
1. Data Exploration and Cleaning: Checked for missing values and analyzed data types.
2. Feature Engineering: Implemented One-Hot Encoding for categorical features like smoker status, region, and sex.
3. Correlation Analysis: Generated a correlation heatmap to visually grasp feature dependencies.
4. Model Training and Evaluation: Split data into training/testing sets, evaluated model performance, and tuned classification thresholds for business optimization.  
