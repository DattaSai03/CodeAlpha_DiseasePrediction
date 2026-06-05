# CodeAlpha_CreditScoring

This project focuses on predicting credit risk using Machine Learning techniques and financial data analysis.

The model analyzes customer financial information and predicts whether a customer is likely to be a good or bad credit risk.

---

# Credit Risk Prediction using Machine Learning

A Machine Learning project that predicts creditworthiness using data preprocessing, feature engineering, class balancing, and multiple classification algorithms.

---

# 🎯 Project Overview

This project applies Machine Learning techniques to classify customer credit risk based on financial and personal information.

## Prediction Classes

* Good Credit Risk
* Bad Credit Risk

## Techniques Used

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* SMOTE Class Balancing
* Logistic Regression
* Random Forest
* XGBoost
* Cross Validation
* Overfitting Analysis

---

# 🚀 Key Achievements

✅ Performed complete preprocessing and feature engineering

✅ Handled imbalanced dataset using SMOTE

✅ Achieved stable model generalization

✅ Reduced overfitting using hyperparameter tuning

✅ Compared multiple Machine Learning algorithms

✅ Achieved best testing accuracy of **72.04%**

---

# 📊 Final Model Results

| Model               | Training Accuracy | Testing Accuracy | Precision | Recall  | F1 Score | ROC-AUC |
| ------------------- | ----------------- | ---------------- | --------- | ------- | -------- | ------- |
| Logistic Regression | 75.18%            | 67.74%           | 77.21%    | 78.36%  | 77.78%   | 60.72%  |
| Random Forest       | 75.29%            | 67.74%           | 75.00%    | 82.84%  | 78.72%   | 60.16%  |
| XGBoost             | 55.58%            | 72.04%           | 72.04%    | 100.00% | 83.75%   | 53.41%  |

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
* Overfitting Analysis

---

# 🧠 Machine Learning Workflow

## Initial Challenges

* Missing values in financial data
* Imbalanced class distribution
* Model overfitting
* Low minority class prediction

---

## Optimized Solution

✅ Applied Missing Value Imputation

✅ Applied Feature Engineering

✅ Applied One-Hot Encoding

✅ Applied StandardScaler

✅ Applied SMOTE for class balancing

✅ Reduced overfitting using hyperparameter tuning

✅ Used Cross Validation for better generalization

---

# 🎯 Final Performance Summary

## Logistic Regression

* Training Accuracy: **75.18%**
* Testing Accuracy: **67.74%**
* Mild Overfitting
* Stable Generalization
* 
<img width="637" height="566" alt="Logistic Regression_Confusion" src="https://github.com/user-attachments/assets/966320f0-f365-4c9b-a47f-a4f35d4820f6" />


## Random Forest

* Training Accuracy: **75.29%**
* Testing Accuracy: **67.74%**
* Mild Overfitting
* Good Recall Performance
  
<img width="633" height="568" alt="Random Forest_Confusion" src="https://github.com/user-attachments/assets/01eedc4c-6d4b-4b7c-8684-7be0f3234efa" />


## XGBoost

* Training Accuracy: **55.58%**
* Testing Accuracy: **72.04%**
* Excellent Generalization
* Highest Testing Accuracy

<img width="635" height="565" alt="XGBoost_Confusion" src="https://github.com/user-attachments/assets/fe6bcf9b-ef40-44c8-a3a5-2f26190e29cb" />


---

# 📉 Overfitting Analysis

The project includes train-test accuracy gap analysis to identify:

* Excellent Generalization
* Mild Overfitting
* Strong Overfitting

This helped optimize model stability and performance.

---

# 🛠️ Technical Stack

## Programming Language

* Python

## Environment

* Google Colab
* Jupyter Notebook

## Libraries Used

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn

---

# 🔍 Data Preprocessing

The following preprocessing steps were performed:

* Missing Value Handling
* Feature Engineering
* One-Hot Encoding
* Feature Scaling
* Outlier Removal
* SMOTE Oversampling
* Train-Test Split

These preprocessing techniques improved model performance and reduced bias.

---

# 🚀 Quick Start

## Installation

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

▶️ Run the Project

Open the notebook in Google Colab or Jupyter Notebook

Load the German Credit Dataset

Run all cells sequentially

Train and evaluate the models

---

# 📁 Project Structure

```text
Task3_CreditScoring/
│
├── CreditScoring.ipynb
├── README.md
├── requirements.txt
│
├── results/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── accuracy_graph.png
│
└── dataset/
    └── german_credit_data.csv
```


---

# 📚 Dataset Used

The dataset used in this project is the German Credit Risk Dataset.

[Download Dataset](https://www.kaggle.com/datasets/kabure/german-credit-data-with-risk?utm_source=chatgpt.com)

## Dataset Information

* Customer Financial Information
* Loan Details
* Credit History
* Demographic Information
* Risk Classification

---

# ⚙️ Machine Learning Workflow

* Data Collection
* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Encoding
* Feature Scaling
* SMOTE Balancing
* Train-Test Split
* Model Training
* Prediction
* Performance Evaluation

---

# 📈 Future Improvements

* Hyperparameter Optimization
* Ensemble Learning
* Deep Learning Models
* Explainable AI (XAI)
* Web Application Deployment
* Real-Time Credit Scoring System

---

# 👤 Author

Datta Sai Srinivas Devulapalli

ML Intern | [LinkedIn Profile](https://www.linkedin.com/in/sai-srinivas-devulapalli-48a592351/)

Developed as part of Machine Learning Internship at Code Alpha

---

# 📄 License

This project is open source and available under the MIT License.
