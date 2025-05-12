# Patient Readmission Prediction

This project focuses on predicting patient readmission status based on hospital visit data. The target variable indicates whether a patient was readmitted within 30 days, after 30 days, or not readmitted at all.

---

## Project Overview

- **Goal**: Classify patients into one of three readmission categories:
  - `NO` (Not readmitted)
  - `<30` (Readmitted within 30 days)
  - `>30` (Readmitted after 30 days)
- **Dataset**: Medical dataset with demographic, admission, and diagnostic information.
- **Techniques Used**:
  - Data Cleaning & Preprocessing
  - Feature Scaling
  - Classification Models (Logistic Regression, Random Forest, XGBoost)
  - Evaluation with Accuracy, F1-Score, precision, recall

---

##  Files

| File | Description |
|------|-------------|
| `Hospital Readmission Prediction.ipynb` | Main Jupyter Notebook with all steps. You can see a full interactive version of this notebook [here](https://nbviewer.org/github/esraa-ehab/Hospital-Readmission-Prediction/blob/main/Hospital%20Readmission%20Prediction.ipynb) |
| `diabetic_data.csv` | Input dataset (replace with actual name if different) |
| `README.md` | Project description |

---

## Requirements

- pandas
- numpy
- plotly
- scikit-learn
- xgboost
