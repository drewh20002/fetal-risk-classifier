# Fetal Risk Classifier

This project builds a machine learning model to classify fetal health risk levels (Normal, Potential Risk, High Risk) using cardiotocogram (CTG) data. The goal is to support midwives and clinical practitioners with an automated, interpretable tool to aid timely decision-making during labour.

---

## Overview

- Models used: Random Forest, XGBoost, Gradient Boosting  
- Data: 2,126 CTG records with 22 features (clinical measurements and time-series summaries)  
- Target: Fetal risk classification into three categories  
- Addressed class imbalance using manual weighting  
- Performance evaluated via macro F1-score, ROC-AUC, and confusion matrix  

---

## Files

- `fetal_risk_classifier.ipynb`: Complete analysis and modeling pipeline  
- `fetal_health.csv`: Dataset used  
- `Document - Fetal Risk Classifer.pdf`: Stakeholder-facing project summary  
- `requirements.txt`: Python package dependencies  

---

## Usage

1. Clone/download repo  
2. Ensure `fetal_health.csv` is in the same folder as the notebook  
3. Open and run `fetal_risk_classifier.ipynb` in Jupyter or VSCode  

> **Note:** If you don’t need to run the code, you can still open and read the notebook file directly in GitHub’s web interface or via Jupyter to view the analysis, results, and visualizations.

---

## Setup

Install dependencies with:

```bash
pip install -r requirements.txt
