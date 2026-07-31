# 🛒 Online Shopper Purchase Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether an online visitor will purchase a product based on browsing behaviour. Multiple machine learning models were developed, compared, and evaluated to identify the best-performing classifier. Model interpretability was also performed using SHAP (SHapley Additive exPlanations).

---

## 🎯 Objectives

- Predict customer purchase intention
- Compare multiple machine learning algorithms
- Improve performance through hyperparameter tuning
- Explain model predictions using SHAP
- Identify the most influential customer behaviour features

---

## 📊 Dataset

Dataset: Online Shoppers Purchasing Intention Dataset

Features include:

- Administrative pages
- Product-related pages
- Bounce Rate
- Exit Rate
- Page Value
- Traffic Type
- Visitor Type
- Month
- Weekend

Target variable:

Revenue
- 0 = No Purchase
- 1 = Purchase

---

## 🤖 Machine Learning Models

The following models were implemented:

- Logistic Regression
- Balanced Logistic Regression
- Decision Tree
- Random Forest
- Tuned Random Forest
- K-Nearest Neighbours (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes

---

## ⚙️ Hyperparameter Tuning

Random Forest was optimized using GridSearchCV to improve predictive performance.

---

## 📈 Model Performance

The Tuned Random Forest achieved the best performance.

Evaluation metrics included:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

## 🔍 Explainable AI (SHAP)

SHAP was used to explain model predictions.

Visualisations include:

- SHAP Summary Plot
- SHAP Waterfall Plot
- Feature Importance

Key finding:

PageValues was the most influential feature affecting purchase prediction.

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SHAP
- Jupyter Notebook

---

## 📂 Repository Structure

```
Online_Shopper_Purchase_Prediction.ipynb
online_shoppers_intention.csv
LICENSE
README.md
```

---

## 👩‍💻 Author

Kazi Kaniz Fatema

GitHub:
https://github.com/KaziKanizFatema
