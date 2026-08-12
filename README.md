# FairLend-Credit: Mitigating Algorithmic Bias in Automated Loan Approval Systems

This repository contains a research-backed Data Science framework designed to predict bank loan eligibility while auditing and mitigating financial credit risks. Developed under an academic framework, this project addresses the critical challenge of **Algorithmic Fairness in FinTech**, ensuring automated credit decisions are accurate, transparent, and legally equitable.

---

## 🎯 Research Objectives & Core Features

Standard machine learning models inherently optimize for statistical accuracy, frequently perpetuating or amplifying historical biases found in demographic and financial data. This project bridges the gap between predictive performance and ethical AI through:

* **Fairness-Aware Machine Learning:** Incorporates **Fairlearn** and bias mitigation algorithms to evaluate disparate impact across sensitive attributes (e.g., gender, age, marital status).
* **Robust Predictive Modeling:** Implements state-of-the-art classification algorithms optimized for complex risk assessment.
* **Algorithmic Auditing (EDA):** Deep statistical profiling and structural analysis of demographic dependencies and historical lending disparities.
* **End-to-End Automated Data Pipeline:** Clean engineering pipelines for robust handling of missing values, structural variance, and synthetic data balancing.

---

## 🛠️ Tech Stack & Research Tools

* **Core Framework:** Python
* **Specialized toolkits:** Fairlearn (Bias Mitigation), Scikit-Learn (Predictive Modeling)
* **Data Pipelines & Analytics:** Pandas, NumPy
* **Statistical Visualization:** Matplotlib, Seaborn
* **Execution Environments:** Google Colab, Kaggle Enterprise Clusters

---

## 📊 Methodology & Model Evaluation

### 1. Dataset & Target Optimization
* **Source:** Kaggle Enterprise Bank Loan Datasets
* **Target Vector:** `Loan_Status` (Approved / Rejected Binary Classification)

### 2. Fairness & Evaluation Metrics
To satisfy rigorous academic benchmarks, the system evaluates models using two distinct lenses:
* **Predictive Performance:** Classification Report, ROC-AUC Curves, Confusion Matrix, and Overall Accuracy Scores.
* **Fairness Metrics:** **Demographic Parity Difference** and **Equalized Odds**, ensuring the predictive parity remains uniform across demographic sub-groups.

> 💡 *[Optional Placeholder: Insert a brief description or mathematical formulation of the Fairness metric you implemented here.]*

### 3. The Accuracy-Fairness Trade-Off
A key contribution of this project is mapping the optimization curve between absolute model accuracy and fairness parity limits, visualized below:

