# 🩺 Diabetes Risk Prediction

A machine learning project that predicts the likelihood of diabetes based on medical diagnostic features using the **Pima Indians Diabetes Dataset** from Kaggle.

---

## 📘 Project Overview
This project explores how machine learning can assist in early diabetes detection.  
It compares multiple classification models — **Logistic Regression** and **Random Forest** — and applies **Bayesian Optimization** for hyperparameter tuning.  
Finally, it visualizes performance using an **ROC curve**.

---

## 🧩 Dataset
**Source:** [Pima Indians Diabetes Database (Kaggle)](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

**Goal:** Predict whether a patient has diabetes based on medical attributes such as:
- Glucose level  
- Blood pressure  
- Insulin  
- BMI  
- Age  

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Handled dataset loading and cleaning  
   - Applied `StandardScaler` for normalization  

2. **Modeling**
   - Logistic Regression  
   - Random Forest Classifier  
   - Random Forest with **BayesSearchCV** (hyperparameter tuning)

3. **Evaluation**
   - Accuracy score  
   - ROC–AUC score  
   - ROC curve visualization  

---

## 📊 Results Summary
| Model | Accuracy | ROC–AUC |
|--------|-----------|----------|
| Logistic Regression | ~75% | — |
| Random Forest | ~74% | — |
| Random Forest (Bayes Search) | ↑ Slightly higher | — |

> Despite similar AUC scores, the Bayesian-tuned model achieved slightly higher accuracy due to optimized parameters improving class separation.

---

## 🧠 Learnings
- Understood full ML workflow: preprocessing → training → tuning → evaluation  
- Learned how hyperparameter tuning affects model performance  
- Gained experience visualizing classifier performance with ROC curves  

---

## 💻 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🗂️ Folder Structure

