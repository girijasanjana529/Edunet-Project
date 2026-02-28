# 📌 Employee Attrition Prediction & Salary Hike Recommendation System

## 📖 Project Overview

Employee attrition is a major challenge for organizations as it leads to increased hiring costs, productivity loss, and workforce instability.

This project develops a **Machine Learning-based HR Decision Support System** that:

* Predicts employee attrition (Yes/No)
* Generates attrition risk scores
* Recommends salary hike percentages
* Explains predictions using SHAP (Explainable AI)

The system helps HR departments make proactive, transparent, and data-driven retention decisions.

---

## 🎯 Problem Statement

Organizations face difficulty in:

* Identifying employees likely to leave
* Understanding key reasons behind attrition
* Making fair and optimized salary hike decisions
* Trusting black-box machine learning models

This project aims to solve these challenges using predictive analytics and explainable AI.

---

## 🚀 Proposed Solution

The system consists of:

1. **Classification Model (Random Forest)**

   * Predicts employee attrition
   * Generates risk category (Low / Medium / High)

2. **Regression Model**

   * Predicts recommended salary hike percentage

3. **SHAP Explainability**

   * Identifies top features influencing each prediction
   * Provides global and local explanations

4. **Streamlit Dashboard**

   * Interactive HR interface
   * Visualizes predictions and insights

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Scikit-learn
* Random Forest Algorithm
* SHAP (Explainable AI)
* Matplotlib
* Streamlit

---

## 🧠 Machine Learning Models

### 🔹 Random Forest Classifier

Used to predict employee attrition.

Key Parameters:

* n_estimators = 200
* criterion = "gini"
* max_features = "sqrt"
* bootstrap = True
* random_state = 42

### 🔹 Random Forest Regressor

Used to recommend salary hike percentage.

---

## 📊 Evaluation Metrics

The classification model was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

Recall was prioritized to ensure high-risk employees are not missed.

---

## 📈 SHAP Explainability

SHAP (SHapley Additive Explanations) was used to:

* Identify top global attrition factors
* Explain individual employee predictions
* Show how each feature increases or decreases attrition probability

This ensures transparency and trust in HR decision-making.

---

## 🔍 Key Insights

* Overtime significantly increases attrition risk.
* Low Job Satisfaction strongly influences employee exit.
* Stock Option Level impacts retention decisions.
* Salary hike recommendations can reduce attrition probability.
* SHAP analysis provides personalized retention insights.

---

## 🏗️ System Architecture

Raw Data
↓
Data Preprocessing
↓
Feature Encoding
↓
Train-Test Split
↓
Random Forest Classification (Attrition Prediction)
↓
Risk Score Generation
↓
Regression Model (Salary Hike Recommendation)
↓
SHAP Explainability
↓
Streamlit Dashboard

---


## 📌 Future Scope

* Integration with real-time HR management systems
* Use of advanced models like XGBoost or Deep Learning
* Employee sentiment analysis using NLP
* Cloud deployment for enterprise use
* Automated retention strategy recommendations

---

## 📜 License

This project is for educational and research purposes.

---

# ⭐ Final Note

This project demonstrates how Machine Learning and Explainable AI can transform HR decision-making by combining prediction accuracy with transparency.
