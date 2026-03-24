# 🟠 ML Lab 07 – Ensemble Learning (Bagging, Boosting, Stacking)

This directory contains the implementations for Lab 7, focusing on ensemble classification techniques applied to the Breast Cancer Wisconsin dataset using Scikit-Learn.

## 📝 Objective
Build, evaluate, and compare **Bagging**, **AdaBoost**, **Gradient Boosting**, and **Stacking** classification models. The goal is to understand how ensemble strategies improve upon individual classifiers.

## 📂 Structure
- `notebook.ipynb` - The primary Jupyter Notebook with step-by-step experiments.
- `ML LAB -7.docx` - The formalized lab report document.
- `outputs/` - Generated visualization assets (ROC curves, Confusion Matrices, Accuracy charts).

## 📊 Evaluation Metrics Computed
- Overall Accuracy
- Confusion Matrix Heatmaps (Seaborn)
- Classification Reports (Precision, Recall, F1-Score)
- Area Under ROC Curve (AUC)

## 🏆 Key Results
**AdaBoost** and **Stacking** achieved the highest testing accuracy. Ensemble methods significantly enhance the performance and robustness of the model, minimizing False Negatives in a critical medical diagnosis scenario.
