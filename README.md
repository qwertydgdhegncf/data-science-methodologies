# 🧠 Data Science Methodologies — CRISP-DM, SEMMA & KDD

This repository showcases **three complete data science projects**, each built using a different methodological framework:
- 🌀 **CRISP-DM** — Business and process-driven approach  
- ⚙️ **SEMMA** — Analytical and model-centric methodology  
- 🔍 **KDD** — Knowledge discovery in databases (research-oriented)

Each notebook walks through every phase of the methodology — from data understanding and preparation to modeling, evaluation, and deployment.

---

## 📂 Notebooks

| Methodology | Focus Area | Notebook | Open in Colab |
|--------------|-------------|-----------|----------------|
| 🌀 **CRISP-DM** | Customer Churn Prediction (IBM Telco dataset) | [`crispdm.ipynb`](./crispdm.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/qwertygdghegncf/data-science-methodologies/blob/main/crispdm.ipynb) |
| ⚙️ **SEMMA** | Student Performance Prediction (UCI dataset) | [`semma.ipynb`](./semma.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/qwertygdghegncf/data-science-methodologies/blob/main/semma.ipynb) |
| 🔍 **KDD** | Credit Card Fraud Detection (Kaggle dataset) | [`kdd.ipynb`](./kdd.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/qwertygdghegncf/data-science-methodologies/blob/main/kdd.ipynb) |

> ☁️ *Click any “Open in Colab” button to run the notebook instantly in Google Colab.*

---

## 🌀 CRISP-DM — Customer Churn Prediction

**Goal:**  
Predict and reduce customer churn by identifying at-risk telecom customers.

**Highlights:**
- CRISP-DM workflow: Business → Data → Preparation → Modeling → Evaluation → Deployment  
- Compared Logistic Regression, Random Forest, and XGBoost  
- Achieved **ROC-AUC = 0.84**, **Average Precision = 0.64**  
- Exported a deployable `model.pkl` with full metrics  

**Dataset:** [IBM Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## ⚙️ SEMMA — Student Performance Prediction

**Goal:**  
Predict final student grades (G3) from behavioral and academic data.

**Highlights:**
- SEMMA process: Sample → Explore → Modify → Model → Assess  
- Feature engineering: `failures_bin`, `studytime_cat`  
- XGBoost achieved **R² = 0.80**, **MAE = 1.19**  
- Explained relationships between study habits and performance  

**Dataset:** [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

---

## 🔍 KDD — Credit Card Fraud Detection

**Goal:**  
Detect fraudulent transactions using both **supervised** and **unsupervised** learning.

**Highlights:**
- Applied full KDD pipeline: Selection → Preprocessing → Transformation → Data Mining → Interpretation  
- **Supervised model:** Logistic Regression with SMOTE → **AUC = 0.96**  
- **Unsupervised model:** Isolation Forest → **AUC = 0.89**  
- Demonstrated hybrid anomaly detection strategy  

**Dataset:** [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## ⚙️ Tools & Libraries
Python · Pandas · NumPy · Scikit-learn · XGBoost · Matplotlib · Seaborn · Imbalanced-learn

Install dependencies:
```bash
pip install -r requirements.txt

