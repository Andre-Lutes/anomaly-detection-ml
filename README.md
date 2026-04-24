# Anomaly Detection with Machine Learning

## 📌 Overview
This project focuses on detecting anomalous patterns in healthcare data using Machine Learning techniques.

The goal is to identify critical cases automatically and support data-driven decision making.

---

## 🧠 Problem
Detect anomalies (outliers) in structured data that may indicate unusual or critical events.

---

## 📊 Data
- Dataset with health-related variables
- Examples:
  - weight_pounds
  - gestation_weeks
  - mother_age

---

## ⚙️ Solution
- Data preprocessing and cleaning
- Feature analysis
- Model training using Random Forest
- Evaluation using classification metrics

---

## 📈 Results
- Achieved ~92% recall
- Model successfully identified most critical cases
- Key variable: **weight_pounds** had strong influence

---

## 🧪 Key Learnings
- Importance of handling imbalanced data
- Model evaluation (Precision, Recall, F1-score)
- Risk of data leakage and how to mitigate it
- Real-world limitation: high performance may not generalize

---

## 🛠️ Tech Stack
- Python
- Pandas
- Scikit-Learn
- BigQuery (data processing)

---

## 🚀 Future Improvements
- Add more variables and datasets
- Test other models (XGBoost, Isolation Forest)
- Improve validation strategy
