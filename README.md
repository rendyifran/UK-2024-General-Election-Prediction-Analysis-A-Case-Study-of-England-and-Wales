# UK 2024 General Election Prediction Analysis  
## Case Study: England & Wales

<p align="center">
  <img src="images/Feature Importance.png" width="30%" />
  <img src="images/Correlation Matrix.png" width="30%" />
  <img src="images/Confusion matrices.png" width="30%" />
</p>

---

## Overview

This project applies supervised machine learning models to predict the winning political party in each constituency for the 2024 UK General Election in England and Wales.

Using constituency-level socioeconomic and electoral features, the study evaluates how different classification algorithms perform in multi-class political outcome prediction.

The objective is to assess model robustness, interpret feature importance, and compare predictive performance across algorithms.

---

## Research Objectives

- Predict the winning party at constituency level.
- Compare classification performance across multiple ML models.
- Identify the most influential predictors of electoral outcomes.
- Evaluate model generalisation and misclassification patterns.

---

## Methodology

### Data
- Constituency-level electoral and demographic indicators  
- Socioeconomic covariates  
- Historical voting patterns  

### Models Implemented

- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbour (KNN)  

### Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrix analysis  

---

## Model Comparison & Insights

- Random Forest demonstrated strong predictive stability and interpretability through feature importance analysis.
- SVM showed competitive performance in high-dimensional feature space.
- KNN performance varied depending on feature scaling and neighbourhood size.

Feature importance analysis highlighted the role of key socioeconomic and historical voting variables in predicting constituency-level outcomes.

---

## Why This Matters

Machine learning-based election modelling contributes to:

- Political data analysis  
- Forecasting research  
- Understanding structural drivers of electoral behaviour  
- Model comparison in multi-class classification tasks  

This study demonstrates how structured constituency-level data can be leveraged for predictive political analytics.

---

## Tools

Python · Pandas · Scikit-learn · Random Forest · SVM · KNN · Model evaluation metrics

---

## Repository Structure

- `images/` – Model outputs and evaluation visualisations  
- `Main_code_election.ipynb` – Full modelling pipeline  
- `Analysis_doc_election.pdf` – Complete research report  
- `README.md`  

---

## Author

Mohamad Rendy Irawan Ifran  
MSc Social and Geographic Data Science  
University College London
