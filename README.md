# Fair Lend Credit Analytics ⚖️💳

A FinTech Data Science project focused on credit risk assessment and algorithmic analysis using Machine Learning.

## 📌 Project Overview
This repository contains a data pipeline and credit scoring model designed to analyze and process loan approvals. Coming from a **Mathematics and Chartered Accountancy (CA Inter)** background, I bridged the gap between financial ledger structures, risk metrics, and data science to prepare clean, structured data for machine learning systems.

## 🛠️ Tech Stack & Data Preprocessing
- **Language:** Python (Google Colab / Jupyter Notebook)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Dataset:** 614 historical loan applicant records featuring financial features like Applicant Income, Co-applicant Income, Loan Amount, and Credit History.

### Key Preprocessing Steps Implemented:
1. **Exploratory Data Analysis (EDA):** Analyzed categorical behaviors and gender matrices against Loan Status via cross-tabulations.
2. **Missing Value Imputation:** Handled missing financial and biographical fields dynamically using Statistical Mode (for categorical features) and Median (for numerical structures).
3. **Label Encoding:** Transformed complex banking string variables into clean machine-readable numerical metrics (0/1).

## 📊 Key Insights & Results
- Successfully verified that a borrower's **Credit History** is the strongest leading indicator for final risk profiling (with a ~79.5% approval distribution for positive history records).
- Resolved features down to a clean, 100% complete dataset layout (`0 null values`) ready for high-performance classifiers like XGBoost.

---
*Created as part of my preparation for a Master's in Data Science (Finance Track).*

