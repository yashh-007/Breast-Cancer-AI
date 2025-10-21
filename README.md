# Breast Cancer Classification AI

## Project Overview
This project uses machine learning to predict **breast cancer diagnosis** (malignant vs. benign) based on the **Wisconsin Breast Cancer dataset**. It demonstrates a **stacked ensemble model** combining XGBoost, LightGBM, and Random Forest to achieve high accuracy (>95%).  

The project includes **model training, evaluation, and visualization**, and produces a Kaggle-ready submission file.

---

## Dataset
- Source: [Kaggle Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- Features: 30 numeric features extracted from cell nuclei images
- Target: `diagnosis` (0 = Benign, 1 = Malignant)
- Total samples: 569

---

## Features
- **Stacked Ensemble Model**: XGBoost + LightGBM + Random Forest  
- **Evaluation Metrics**:
  - Accuracy
  - AUC Score
  - Confusion Matrix
  - ROC Curve
- **Interpretability**: SHAP feature importance (optional)  
- **Submission**: Outputs predictions in `breast_cancer_submission.csv`  

---

## How to Run
1. Install required libraries:
   ```bash
   pip install xgboost lightgbm shap matplotlib seaborn
# Breast-Cancer-AI
