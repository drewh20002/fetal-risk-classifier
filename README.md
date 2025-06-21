# Fetal Risk Classifier

This project uses supervised machine learning techniques to classify fetal health risks (Normal, Suspect, Pathological) based on cardiotocogram (CTG) data.

## 🔍 Overview

- Built using Python and scikit-learn
- Trained and evaluated multiple classifiers (Random Forest, XGBoost)
- Evaluated using F1 score, ROC-AUC, and confusion matrix
- Visualised key metrics and model performance
- Aimed to assist with early identification of potential fetal distress

## 📁 Files

- `fetal_risk_classifier.ipynb`: The main notebook containing data loading, preprocessing, modelling, and evaluation
- `fetal_health.csv`: Dataset used (from UCI Machine Learning Repository)

## 📊 Dataset

- Source: [UCI CTG Dataset](https://archive.ics.uci.edu/ml/datasets/Cardiotocography)
- Features: 21 physiological signals from CTG
- Target: Fetal health status (1 = Normal, 2 = Suspect, 3 = Pathological)

## 🚀 How to Run

1. Clone this repository
2. Open `fetal_risk_classifier.ipynb` in Jupyter or VSCode
3. Run the cells from top to bottom

Make sure `fetal_health.csv` is in the same directory as the notebook.

## ✅ Requirements

- Python 3.9+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost 

Install with:
```bash
pip install -r requirements.txt
