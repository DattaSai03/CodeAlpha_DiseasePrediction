# CodeAlpha_DiseasePrediction
This project focuses on predicting the likelihood of diseases using structured medical data and machine learning classification techniques. The model analyzes patient-related attributes such as symptoms, age, and blood test results to assist in early disease detection.
# Disease Prediction from Medical Data using Machine Learning

A machine learning project that predicts diseases using medical datasets with high accuracy through multiple classification algorithms.

---

# 🎯 Project Overview

This project applies machine learning techniques to predict diseases from structured medical data.

Diseases Covered:
- Heart Disease
- Diabetes
- Breast Cancer

Algorithms Used:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

Key Achievement:
- Achieved **98.54% accuracy** for Heart Disease prediction using Random Forest
- Achieved **98.25% accuracy** for Breast Cancer prediction using SVM
- Improved Diabetes prediction accuracy from **75.32% → 76.62%** using data preprocessing

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

### Heart Disease (Random Forest)

- Accuracy: 98.54%
- Precision: 1.0000
- Recall: 0.9709
- F1 Score: 0.9852

### Diabetes (Random Forest)

- Accuracy: 76.62%
- Precision: 0.6557
- Recall: 0.7273
- F1 Score: 0.6897

### Breast Cancer (SVM)

- Accuracy: 98.25%
- Precision: 1.0000
- Recall: 0.9535
- F1 Score: 0.9762

---

# 🛠️ Technical Stack

### Programming Language
- Python

### Environment
- Google Colab
- Jupyter Notebook

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

### Machine Learning Techniques
- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Classification Models
- Performance Evaluation

---

# 🚀 Quick Start

## Installation

```bash
pip install pandas numpy matplotlib scikit-learn xgboost

▶️ Run the Project

Open the notebook in Google Colab or Jupyter Notebook and run all cells.

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
🔍 Data Preprocessing

The Diabetes dataset contained medically invalid zero values in:

Glucose
BloodPressure
SkinThickness
Insulin
BMI

These values were replaced with median values to improve model performance.

📚 Datasets Used
UCI Machine Learning Repository

Datasets:

Heart Disease Dataset
PIMA Indians Diabetes Dataset
Breast Cancer Wisconsin Dataset
🧠 Machine Learning Workflow
Data Collection
Data Loading
Data Cleaning
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

Srinivas

ECE Student | Machine Learning Enthusiast

Developed as part of Machine Learning Internship and Practice Projects.

📄 License

This project is open source and available under the MIT License.
