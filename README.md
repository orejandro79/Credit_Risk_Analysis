# Credit Risk — PD Modeling (Prototype)

**Purpose:** Prototype a Probability of Default (PD) model for retail personal loans.  
**Dataset:** `Task 3 and 4_Loan_Data.csv` (columns include `credit_lines_outstanding`, `loan_amt_outstanding`, `total_debt_outstanding`, `income`, `years_employed`, `fico_score`, `default`).  
**Reference:** CREDIT RISK ANALYSIS TASK.docx. :contentReference[oaicite:2]{index=2}

---

## Contents
- `notebook.ipynb` — Jupyter notebook with ETL, EDA, Feature Engineering, Modeling (Logistic, RandomForest, XGBoost), and evaluation.
- `Task 3 and 4_Loan_Data.csv` — dataset (place in notebook folder).
- `xgb_pd_model.joblib` — trained XGBoost model (if saved).
- `median_vals.joblib` — medians for imputation (if saved).
- `README.md` — this file.

---

## How to run
1. Install required packages (recommended to use a virtual env):
   ```bash
   pip install -r requirements.txt
   # or
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn joblib


