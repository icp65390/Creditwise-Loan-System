---

## Author

**Ishwor C Paudyal**
Data Analyst | Python & Machine Learning

GitHub: [https://github.com/icp65390](https://github.com/icp65390)

---
# CreditWise – Loan Approval Prediction (End‑to‑End ML Project)

> **Role Target:** Data Analyst | Junior Machine Learning Engineer
> **Skills Demonstrated:** Python, Data Analysis, Feature Engineering, Machine Learning, Model Evaluation

---

##  Recruiter Snapshot

**CreditWise** is a complete, production-style Machine Learning project that predicts **loan approval decisions** using applicant financial and demographic data.

This project showcases my ability to:

* Work with real-world, imperfect datasets
* Apply the full data science lifecycle
* Build, evaluate, and compare ML models
* Write clean, readable, and explainable code

---

##  Business Problem

Financial institutions must evaluate loan applications efficiently while minimizing risk.

**Goal:** Predict whether a loan should be **approved or rejected** based on historical applicant data.

**Impact:**

* Faster decision-making
* Reduced default risk
* Data-driven credit assessment

---

##  Solution Approach

This project follows a structured ML pipeline:

1. Data ingestion and validation
2. Data cleaning and missing value handling
3. Exploratory Data Analysis (EDA)
4. Feature engineering and transformation
5. Model training and comparison
6. Performance evaluation

---

##  Tech Stack

* **Programming:** Python
* **Data Analysis:** pandas, numpy
* **Visualization:** matplotlib, seaborn
* **Machine Learning:** scikit-learn
* **Environment:** Jupyter Notebook

---

##  Repository Structure

```
CreditWise/
│
├── credit_wise.ipynb        # End-to-end ML notebook
├── loan_approval_data.csv  # Input dataset
├── README.md               # Project documentation
```

---

##  Dataset Overview

The dataset includes:

* Applicant income & financial indicators
* Credit history
* Debt-to-Income (DTI) ratio
* Employment & demographic features

**Target Variable:** `Loan_Approved`

* `1` → Approved
* `0` → Not Approved

---

##  Exploratory Data Analysis (EDA)

Key insights extracted:

* Distribution patterns of income and credit features
* Relationship between credit history and loan approval
* Detection of missing values and outliers

EDA helped guide feature engineering and model selection.

---

##  Data Preprocessing

* Missing value imputation:

  * Numerical → Mean
  * Categorical → Most frequent
* Encoding categorical variables into numerical format
* Feature scaling using **StandardScaler**

---

##  Feature Engineering

* Created derived features to improve model learning
* Example:

  * Squared Debt-to-Income Ratio (`DTI_Ratio_sq`)

---

##  Models Trained

| Model                     | Purpose                       |
| ------------------------- | ----------------------------- |
| Logistic Regression       | Baseline, interpretable model |
| K-Nearest Neighbors (KNN) | Distance-based classification |
| Gaussian Naive Bayes      | Probabilistic baseline model  |

---

##  Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

This allows objective comparison and selection of the best-performing model.

---

##  Key Takeaways

* Data preprocessing significantly impacts model performance
* Feature engineering improves prediction quality
* Simple models can perform competitively with proper preparation

---

## How to Run Locally

```bash
git clone https://github.com/icp65390/CreditWise.git
cd CreditWise
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
```

Run `credit_wise.ipynb` step by step.



⭐ If you are a recruiter or hiring manager, feel free to explore the notebook and reach out!
