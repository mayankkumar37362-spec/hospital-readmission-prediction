# 🏥 Hospital Readmission Prediction & Healthcare Analytics

Predicting 30-day hospital readmissions using Machine Learning and Healthcare Analytics to support early risk identification, improve patient outcomes, and optimize hospital resource utilization.

---

# 📌 Project Overview

Hospital readmissions within 30 days are a major challenge for healthcare systems, leading to increased operational costs, resource utilization, and reduced quality of patient care.

This project develops an end-to-end healthcare analytics pipeline that combines **Exploratory Data Analysis (EDA), Feature Engineering, Machine Learning, and Power BI Dashboarding** to identify key factors influencing patient readmissions and build predictive models for early risk assessment.

---

# 🎯 Business Objective

The objective of this project is to:

- Predict patients at risk of 30-day hospital readmission
- Identify major clinical and operational factors contributing to readmissions
- Support healthcare professionals in proactive patient management
- Visualize hospital performance through an interactive Power BI dashboard

---

# 📂 Dataset

The dataset contains approximately **120,000 hospital admission records** including:

- Patient demographics
- Admission & discharge details
- Diagnosis information
- Comorbidities
- Laboratory results
- Hospital characteristics
- Treatment costs
- Clinical measurements

Target Variable:

```
readmitted_30d
```

---

# 🛠 Tech Stack

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Power BI

### Machine Learning

- Scikit-learn
- XGBoost

### Development

- Jupyter Notebook
- Git
- GitHub

---

# 📊 Exploratory Data Analysis

Performed detailed exploratory analysis to identify factors influencing readmission.

Major analyses include:

- Readmission Rate by Diagnosis Category
- Readmission Rate by Admission Type
- Readmission Rate by Ward Type
- Readmission Rate by Discharge Type
- Patient Age Distribution
- Monthly Admission Trends
- Average Length of Stay Analysis
- Clinical Feature Distribution
- Treatment Cost Analysis

---

# ⚙️ Feature Engineering

Created domain-specific healthcare features including:

- Length of Stay (LOS)
- Cost Per Day
- Diabetes Status
- Kidney Function Category
- Blood Pressure Status
- Anaemia Indicator
- Frequent Patient Flag
- High Comorbidity Flag
- Multiple Diagnoses Flag
- Admission Month
- Admission Day

---

# 🤖 Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- Balanced Logistic Regression
- Decision Tree
- Tuned Decision Tree
- Random Forest
- XGBoost

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

# 🏆 Best Performing Model

**XGBoost** delivered the best balance between identifying high-risk patients and overall predictive performance.

Key strengths:

- Highest Recall among tree-based models
- Better handling of class imbalance
- Improved predictive capability for readmission risk

---

# 📈 Power BI Dashboard

An interactive dashboard was developed to monitor hospital performance and readmission trends.

Dashboard includes:

- KPI Cards
- Readmission Rate by Diagnosis Category
- Readmission Rate by Admission Type
- Readmission Rate by Ward Type
- Readmission Rate by Discharge Type
- Patient Age Distribution
- Average Length of Stay by Diagnosis Category
- Interactive Filters

*(Dashboard preview can be added below.)*

```
📷 dashboard.png
```

---

# 📁 Repository Structure

```
Hospital-Readmission-Prediction/
│
├── data/
├── notebook/
│   └── Hospital_Readmission.ipynb
│
├── dashboard/
│   └── Healthcare.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

# 🚀 Future Improvements

- SHAP Explainability
- Hyperparameter Optimization
- Feature Importance Dashboard
- Deployment using Streamlit
- Real-time Prediction API

---

# 👨‍💻 Author

**Mayank Kumar**

Electronics & Communication Engineering  
National Institute of Technology Raipur

GitHub:
https://github.com/mayankkumar37362-spec

---

## ⭐ If you found this project useful, consider giving it a star!
