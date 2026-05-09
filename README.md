# credit-risk-loan-default
credit risk &amp; loan default prediction using ML 
# 🏦 Credit Risk & Loan Default Prediction

![Python](https://img.shields.io/badge/Python-3.14-blue)
![ML](https://img.shields.io/badge/ML-XGBoost-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Problem Statement
Banks lose millions every year due to loan defaults.
This project builds a machine learning model to predict
whether a loan applicant will default — enabling smarter
lending decisions.

## 🎯 Objective
- Identify key risk factors driving loan defaults
- Build a classification model to predict default probability
- Deliver actionable insights via visual analysis

## 📊 Dataset
- **Source:** Lending Club Loan Dataset (Kaggle)
- **Size:** 22,60,701 rows × 151 columns
- **Period:** 2007 to 2018
- **Target:** loan_status (Fully Paid / Charged Off)

## 🔍 Project Workflow
1. Exploratory Data Analysis (EDA)
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Handling Class Imbalance (SMOTE)
5. Model Building & Evaluation
6. Dashboard Creation (Power BI)

## 📈 Model Performance
| Model | ROC-AUC Score |
|---|---|
| Logistic Regression | 0.9106 |
| **XGBoost** | **0.9228** ✅ |

## 🔑 Key Findings
- Overall default rate: **19.96%**
- Grade G loans have **49.9% default rate** (highest risk)
- Top predictors: **Home Ownership, Loan Grade, DTI Ratio**
- Model correctly identifies **92.28%** of default cases

## 🛠️ Tech Stack
- **Language:** Python 3.14
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost,
  Matplotlib, Seaborn, Imbalanced-learn
- **Dashboard:** Power BI
- **Version Control:** Git & GitHub

## 📁 Project Structure

credit-risk-project/
├── data/
│   ├── raw/             ← Original dataset
│   └── processed/       ← Cleaned dataset
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   └── 03_Modeling.ipynb
├── outputs/             ← Saved model, plots
├── dashboard/           ← Power BI file
└── README.md

## 🚀 How to Run
```bash
# 1. Clone the repo
git clone https://github.com/YourUsername/credit-risk-loan-default.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open notebooks in order
jupyter notebook
```

## 📬 Contact
**Choppa Penchala Praveen** — [LinkedIn Profile URL - www.linkedin.com/in/choppa-penchala-praveen-339b96249] — penchalapraveen221@gmail.com
