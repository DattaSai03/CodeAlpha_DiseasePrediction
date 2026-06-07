# 📌 Handwritten Digit & Character Recognition System

---

## 🧠 Deep Learning using CNN (MNIST + EMNIST)

---

## 📖 Project Overview

This project is a Deep Learning-based Image Classification System that recognizes:

- 🔢 Handwritten digits (0–9) using MNIST dataset  
- 🔤 Handwritten alphabets (A–Z) using EMNIST Letters dataset  

The system uses **Convolutional Neural Networks (CNNs)** for high-accuracy image recognition and can predict both digits and letters from handwritten images.

---

## 📊 Datasets Used

### 🔢 MNIST Dataset (Digits 0–9)
- 60,000 training images  
- 10,000 test images  
- Grayscale handwritten digits  

📌 Dataset Link:  
https://www.kaggle.com/datasets/hojjatk/mnist-dataset  

---

### 🔤 EMNIST Letters Dataset (A–Z)
- 88,800+ images  
- 26 classes (A–Z letters)  
- Extended MNIST dataset for alphabets  

📌 Dataset Link:  
https://www.kaggle.com/datasets/crawford/emnist  

---

## 🎯 Objectives

- Build separate CNN models for MNIST and EMNIST  
- Achieve high accuracy with minimal overfitting  
- Improve generalization using augmentation & regularization  
- Test models on real-world handwritten images  
- Visualize performance using graphs and confusion matrix  

---

## 🧠 Model Performance

### 🔢 MNIST Model Results
- Training Accuracy: 99.49%  
- Testing Accuracy: 99.28%  
- Overfitting Gap: 0.21%  
- Generalization: Excellent ✅  

---

### 🔤 EMNIST Model Results
- Training Accuracy: 97.05%  
- Testing Accuracy: 93.56%  
- Overfitting Gap: 3.49%  
- Generalization: Excellent ✅  

---

## 🏗️ Model Architecture (CNN)

- Conv2D Layers (Feature Extraction)  
- MaxPooling Layers (Downsampling)  
- Batch Normalization (Stability)  
- Dropout (Overfitting Reduction)  
- Flatten Layer  
- Dense Fully Connected Layers  
- Softmax Output Layer  

---

## ⚙️ Techniques Used

### 🧹 Data Preprocessing
- Grayscale conversion  
- Image resizing (28x28)  
- Normalization (0–1 scaling)  
- Label encoding  

---

### 🔄 Data Augmentation (EMNIST)
- Rotation  
- Zoom  
- Width shift  
- Height shift  

---

### 🧠 Regularization
- Dropout layers  
- Batch Normalization  
- Early Stopping  

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  
- Training vs Validation Curves  

---

## 📊 Results Summary

| Model  | Training Accuracy | Testing Accuracy | Overfitting Gap |
|--------|------------------|------------------|------------------|
| MNIST  | 99.49%           | 99.28%           | 0.21%            |
| EMNIST | 97.05%           | 93.56%           | 3.49%            |

---

## 🧪 Testing

The models were tested using:

- ✔ Test dataset images  
- ✔ Random handwritten images uploaded by users  
- ✔ Real-world images captured externally  

### 🔍 Testing Steps
- Upload image  
- Convert to grayscale  
- Resize to 28×28  
- Normalize pixel values  
- Predict using trained CNN model  

---

## 📉 Visual Results

- Confusion Matrix (MNIST & EMNIST)  
- Accuracy Graphs  
- Loss Curves  

These results confirm strong learning performance and good generalization.

---

## 🚀 Key Achievements

- Achieved 99%+ accuracy on MNIST  
- Achieved 93%+ accuracy on EMNIST  
- Built 2 independent CNN models  
- Reduced overfitting using regularization  
- Successfully tested on real-world images  
- Improved generalization using data augmentation  

---

## 🧰 Tech Stack

- Python 🐍  
- TensorFlow / Keras 🤖  
- NumPy  
- Matplotlib  
- Seaborn  
- OpenCV  
- Scikit-learn  
- Google Colab  

---

## 📁 Project Structure
```
Handwritten-Recognition-System/
│
├── mnist_model.keras
├── emnist_letters_model.keras
│
├── notebooks/
│ └── training.ipynb
│
├── results/
│ ├── confusion_matrix_mnist.png
│ ├── confusion_matrix_emnist.png
│ ├── accuracy_graph.png
│ └── loss_graph.png
│
└── README.md
```


---

## 🔮 Future Improvements

- 🚀 Deploy as a web app (Streamlit / Flask)  
- 📱 Mobile app integration for live prediction  
- 🎥 Webcam-based real-time recognition  
- 🧠 Upgrade to ResNet / CNN-LSTM hybrid models  
- 🔤 Combine MNIST + EMNIST into one unified model  
- ✍️ Add drawing canvas for live handwriting prediction  
- ⚡ Optimize model for edge devices (TensorFlow Lite)  

---

## 👤 Author

**Datta Sai Srinivas**  
ML Intern | Deep Learning Enthusiast  

🔗 LinkedIn:  
https://www.linkedin.com/in/sai-srinivas-devulapalli-48a592351/  

---

## 📄 License

This project is licensed under the MIT License.

