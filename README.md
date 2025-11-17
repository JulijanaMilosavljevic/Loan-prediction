# Loan Approval Prediction

**Repository:** [loan-prediction](https://github.com/JulijanaMilosavljevic/loan-prediction)  
**Project type:** Binary Classification (Tabular Data)  
**Goal:** Predict loan approval (Yes/No) using applicant financial and demographic features.  

---

## Project Overview

This project demonstrates an **end-to-end machine learning workflow** in the style of Andrew Ng’s courses:

1. **Problem Definition** – Understand business objective and define ML task.  
2. **Data Exploration** – Inspect data, identify missing values, and analyze distributions.  
3. **Data Cleaning & Feature Engineering** – Impute missing values, create derived features such as `TotalIncome` and `DebtToIncome`, bin continuous variables, and log-transform skewed data.  
4. **Baseline Model** – Logistic Regression to establish a simple benchmark.  
5. **Advanced Model** – Random Forest with hyperparameter tuning using GridSearchCV.  
6. **Evaluation** – Classification report, ROC curve, confusion matrix, and ROC-AUC metric.  
7. **Business Insights** – Interpretation of features, discussion of limitations, and potential next steps.  

---
## Key Highlights

- **Data Processing & Cleaning:** Handling missing values, type conversions, and feature engineering.  
- **Feature Engineering:** `TotalIncome`, `DebtToIncome`, loan amount bins, and log transforms.  
- **Modeling:** Logistic Regression baseline; Random Forest with hyperparameter tuning.  
- **Evaluation:** Precision, Recall, F1-score, ROC-AUC, confusion matrix.  
- **Interpretability:** Clear explanation of feature importance and business impact.

---

## Why This Project Matters

- Demonstrates **end-to-end ML skills** expected from a Junior Applied Scientist.  
- Shows **practical feature engineering and model evaluation** techniques.  
- Provides **readable, modular, and reproducible code** suitable for interview discussion.  
- Allows interviewer to quickly see your **understanding of ML workflow and business application**.

---

## Results & Insights (Summary)

- **Best model:** Random Forest with tuned hyperparameters.  
- **Performance:** ROC-AUC > 0.80 (on test set)  
- **Key predictors:** `Credit_History`, `TotalIncome`, `DebtToIncome`, `Property_Area`  
- Insights can guide loan approval policies and risk assessment.

---
## Files

- `loan_prediction.ipynb` – main notebook with full workflow  
- `loan.csv` – dataset used in the notebook, located at `/content/loan.csv` in Colab  

> Note: In Colab, upload the CSV to `/content/` so the notebook can read it correctly.

---

## How to Run

1. Open `loan_prediction.ipynb` in **Google Colab**.  
2. Upload `loan.csv` to `/content/`.  
3. Run the notebook cells step by step to reproduce data cleaning, modeling, and evaluation.  

---
## License

MIT
