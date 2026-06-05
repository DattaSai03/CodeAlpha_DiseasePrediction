# Credit Scoring Prediction using Machine Learning

A Machine Learning project that predicts customer credit risk using financial and demographic data with advanced preprocessing, feature engineering, class balancing, and classification models.

---

# 🎯 Project Overview

This project focuses on predicting whether a customer is a good or bad credit risk using Machine Learning algorithms.

The system analyzes customer financial information and classifies applicants for credit scoring and loan approval support.

---

# 💳 Credit Risk Classification

## Classes Covered

* Good Credit Risk
* Bad Credit Risk

---

# 🚀 Techniques Used

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* SMOTE Oversampling
* Logistic Regression
* Random Forest
* XGBoost
* Cross Validation
* Overfitting Detection

---

# 🏆 Key Achievements

✅ Performed complete end-to-end Machine Learning workflow

✅ Applied Feature Engineering for better prediction performance

✅ Handled class imbalance using SMOTE

✅ Reduced overfitting using regularization and hyperparameter tuning

✅ Achieved stable model generalization

✅ Compared multiple Machine Learning models

✅ Evaluated models using multiple performance metrics

---

# 📊 Final Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| ------------------- | -------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 69.89%   | 77.08%    | 82.84% | 79.86%   | 60.10%  |
| Random Forest       | 65.05%   | 75.94%    | 75.37% | 75.66%   | 59.62%  |
| XGBoost             | 68.28%   | 77.37%    | 79.10% | 78.22%   | 59.16%  |

---

# 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* Cross Validation Accuracy

---

# 🧠 Machine Learning Workflow

## Data Preprocessing

The following preprocessing techniques were applied:

* Missing Value Handling
* Outlier Removal
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* Train-Test Split
* SMOTE Oversampling

---

# ⚙️ Feature Engineering

Additional meaningful features were created:

* Credit_per_Duration
* High_Credit
* Is_Young

These engineered features improved the learning capability of the models.

---

# ⚖️ Overfitting Reduction Techniques

To improve generalization and reduce overfitting:

✅ Regularization applied in Logistic Regression

✅ Limited tree depth in Random Forest

✅ Reduced estimators and learning rate in XGBoost

✅ Applied Cross Validation

✅ Applied Feature Scaling

✅ Used SMOTE carefully for class balancing

---

# 📉 Model Generalization Analysis

## Logistic Regression

* Mild Overfitting
* Best overall balanced performance

## Random Forest

* Slight overfitting observed
* Good recall performance

## XGBoost

* Excellent generalization
* Stable prediction capability

---

# 📊 Visualizations Included

* Class Distribution Graph
* Confusion Matrix
* ROC Curve
* Accuracy Comparison Graph

---

# 🛠️ Technical Stack

## Programming Language

* Python

## Environment

* Google Colab
* Jupyter Notebook

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn

---

# 🔍 Dataset Information

The project uses the German Credit Dataset for predicting customer credit risk.

## Dataset Features

* Age
* Sex
* Job
* Housing
* Saving Accounts
* Checking Account
* Credit Amount
* Duration
* Purpose

## Target Variable

* Good Credit Risk
* Bad Credit Risk

---

# ⚙️ Machine Learning Models Used

## Logistic Regression

* Applied L2 Regularization
* Balanced class weights

## Random Forest

* Controlled tree depth
* Reduced overfitting using min samples constraints

## XGBoost

* Learning rate tuning
* Regularization
* Column sampling
* Subsampling

---

# 🚀 Quick Start

## Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

---

# ▶️ Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook

2. Download the German Credit Dataset

3. Update dataset path

4. Run all notebook cells sequentially

5. Train models and evaluate results

---

# 📁 Project Structure

Credit_Scoring_Prediction/
│
├── CreditScoring.ipynb
├── README.md
├── requirements.txt
│
├── models/
│   ├── logistic_regression.pkl
│   ├── random_forest.pkl
│   └── xgboost_model.pkl
│
├── results/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── accuracy_comparison.png
│
└── dataset/
└── german_credit_data.csv

---

# 📚 Dataset Used

## German Credit Dataset

The dataset contains customer financial and demographic details used for credit risk classification.

---

# 📈 Future Improvements

* Implement Deep Learning Models
* Hyperparameter Optimization using GridSearchCV
* Deploy as a Web Application
* Add Real-Time Credit Risk Prediction
* Improve ROC-AUC Performance
* Add Explainable AI (XAI)

---

# 👤 Author

Datta Sai Srinivas Devulapalli

ML Intern | LinkedIn Profile

Developed as part of Machine Learning Internship

---

# 📄 License

This project is open source and available under the MIT License.

