# CodeAlpha_DiseasePrediction

This project focuses on predicting the likelihood of diseases using structured medical data and machine learning classification techniques.  

The model analyzes patient-related attributes such as symptoms, age, blood test results, and other medical parameters to assist in early disease detection.

---

# Disease Prediction from Medical Data using Machine Learning

A machine learning project that predicts diseases using multiple medical datasets with high accuracy through classification algorithms.

---

# 🎯 Project Overview

This project applies machine learning techniques to predict diseases from structured medical datasets.

## Diseases Covered
- Heart Disease
- Diabetes
- Breast Cancer

## Algorithms Used
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

---

# 🚀 Key Achievements

✅ Achieved **98.54% accuracy** for Heart Disease prediction using Random Forest  

✅ Achieved **98.25% accuracy** for Breast Cancer prediction using SVM  

✅ Improved Diabetes prediction accuracy from **75.32% → 76.62%** using data preprocessing techniques  

---

# 📊 Results

| Dataset | Best Model | Accuracy |
|----------|------------|-----------|
| Heart Disease | Random Forest | 98.54% |
| Breast Cancer | SVM | 98.25% |
| Diabetes | Random Forest | 76.62% |

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# ❤️ Heart Disease Prediction (Random Forest)

- Accuracy: **98.54%**
- Precision: **1.0000**
- Recall: **0.9709**
- F1 Score: **0.9852**

## Confusion Matrix

(Add Screenshot Here)

---

# 🩺 Diabetes Prediction (Random Forest)

# 📈 Model Improvements

## Initial Model Performance
- Basic preprocessing only
- Raw medical data used directly
- Diabetes dataset contained invalid zero values
- Lower diabetes prediction accuracy

---

## Optimized Model Performance

✅ Replaced medically invalid zero values with median values  

✅ Applied Feature Scaling using StandardScaler  

✅ Used multiple classification algorithms for comparison  

✅ Evaluated models using Accuracy, Precision, Recall, F1 Score, and Confusion Matrix  

✅ Improved Diabetes prediction accuracy from **75.32% → 76.62%**


- Accuracy: **76.62%**
- Precision: **0.6557**
- Recall: **0.7273**
- F1 Score: **0.6897**

## Confusion Matrix

(Add Screenshot Here)

---

# 🎗️ Breast Cancer Prediction (SVM)

- Accuracy: **98.25%**
- Precision: **1.0000**
- Recall: **0.9535**
- F1 Score: **0.9762**

## Confusion Matrix

(Add Screenshot Here)

---

# 🛠️ Technical Stack

## Programming Language
- Python

## Environment
- Google Colab
- Jupyter Notebook

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

---

# 🧠 Machine Learning Techniques Used

- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Classification Algorithms
- Performance Evaluation
- Confusion Matrix Analysis

---

# 🔍 Data Preprocessing

The Diabetes dataset contained medically invalid zero values in the following columns:

- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI

These invalid values were replaced with median values to improve model performance and prediction accuracy.

---

# 🚀 Quick Start

## Installation

```bash
pip install pandas numpy matplotlib scikit-learn xgboost

▶️ Run the Project
Open the notebook in Google Colab or Jupyter Notebook
Upload all dataset CSV files
Run all cells sequentially

📁 Project Structure
DiseasePrediction/
│
├── Disease_Prediction_Project.ipynb
├── heart.csv
├── diabetes.csv
├── breast_cancer.csv
├── screenshots/
│   ├── heart_confusion_matrix.png
│   ├── diabetes_confusion_matrix.png
│   └── cancer_confusion_matrix.png
├── README.md


# 📚 Datasets Used

The datasets used in this project were originally sourced from the UCI Machine Learning Repository and accessed through Kaggle.

## Datasets
- Heart Disease Dataset
- PIMA Indians Diabetes Dataset
- Breast Cancer Wisconsin Dataset

## Dataset Links

- Heart Disease Dataset  
  https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

- PIMA Indians Diabetes Dataset  
  https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

- Breast Cancer Wisconsin Dataset  
  https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## Note

All required CSV files are also included in this repository for easy access and reproducibility.


⚙️ Machine Learning Workflow

Data Collection
Data Loading
Data Cleaning
Data Preprocessing
Feature Scaling
Train-Test Split
Model Training
Prediction
Model Evaluation
Performance Comparison

📈 Future Improvements
Add Hyperparameter Tuning
Implement Cross Validation
Deploy as Web Application
Add Real-time User Input Prediction
Use Deep Learning Models
Improve Diabetes Prediction Accuracy
👨‍💻 Author

Datta Sai Srinivas Devulapalli
ML Intern | https://www.linkedin.com/in/sai-srinivas-devulapalli-48a592351/
Developed as part of Machine Learning Internship at Code Alpha

📄 License

This project is open source and available under the MIT License.
