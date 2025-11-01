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
pip install -r requirements.txt


## 📰 Medium Articles  

Dive deeper into the full write-ups for each methodology — including project walkthroughs, visuals, and reflections on results and learning outcomes.  

- [**CRISP-DM:** Predicting Customer Churn — Step by Step](https://medium.com/@siddharthrao.kartik/article-1-crisp-dm-predicting-customer-churn-step-by-step-c31de2d5fb7a)  
  A business-driven case study that walks through all six CRISP-DM phases — from defining churn objectives to deploying an interpretable XGBoost model for telecom retention.

- [**SEMMA:** Predicting Student Performance](https://medium.com/@siddharthrao.kartik/article-2-semma-predicting-student-performance-1c282dc3b62d)  
  A behavioral data analysis project using the SEMMA methodology to predict student exam grades, featuring exploratory correlations and interpretable regression modeling.

- [**KDD:** Detecting Credit Card Fraud](https://medium.com/@siddharthrao.kartik/article-3-kdd-detecting-credit-card-fraud-2aee36c3aff9)  
  A research-oriented knowledge discovery project applying both supervised and unsupervised learning to uncover fraud patterns in large-scale transaction data.

> 📚 *Each article highlights how structured methodologies like CRISP-DM, SEMMA, and KDD shape the data science workflow — from exploration to deployment and knowledge extraction.*


## 🎥 YouTube Walkthroughs  

Watch complete video walkthroughs for each project — covering dataset overview, step-by-step methodology, model building, and interpretation of results.  

- [**CRISP-DM:** Customer Churn Prediction Walkthrough](https://www.youtube.com/watch?v=gW9dZkfp6H8)  
  A full guided explanation of the CRISP-DM project — including data understanding, feature engineering, model comparison (Logistic Regression, Random Forest, XGBoost), and evaluation with ROC and F1 metrics.

- [**SEMMA:** Student Performance Prediction Walkthrough](https://www.youtube.com/your-semma-link)  
  A visual exploration of the SEMMA process — from sampling and exploration to regression modeling with XGBoost, showing how behavioral and academic factors influence performance.

- [**KDD:** Credit Card Fraud Detection Walkthrough](https://www.youtube.com/your-kdd-link)  
  A detailed video on applying the KDD process to detect fraud — explaining both supervised (Logistic Regression + SMOTE) and unsupervised (Isolation Forest) modeling approaches and how to interpret the results.

> 🎧 *Each video is a concise, 3-4 minute project walkthrough designed for presentation and portfolio demonstration.*
