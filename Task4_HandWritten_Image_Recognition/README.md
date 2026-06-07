# 🧠 CodeAlpha | Handwritten Digit & Character Recognition System

<p align="center">
  <img src="https://img.shields.io/badge/Deep%20Learning-CNN-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Datasets-MNIST%20%7C%20EMNIST-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Accuracy-99%25%20%7C%2093%25-success?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Framework-TensorFlow-red?style=for-the-badge"/>
</p>

---

## 🚀 Project Overview

This project is a **high-performance Deep Learning system** designed to recognize:

- 🔢 Handwritten digits (0–9)
- 🔤 Handwritten alphabets (A–Z)

It leverages **Convolutional Neural Networks (CNNs)** trained on **MNIST and EMNIST datasets** to achieve strong real-world generalization.

The system is capable of processing handwritten images and predicting characters with **near-human-level accuracy on digits**.

---

## 🎯 Problem Statement

Handwritten text recognition is a challenging computer vision problem due to:

- Variations in handwriting styles
- Noise in input images
- Class similarity (e.g., O vs 0, I vs 1)
- Dataset imbalance in extended alphabets

This project aims to build a **robust and scalable recognition system** using deep learning.

---

## 🧠 Solution Architecture

A **CNN-based hierarchical feature extractor** is used:

- Low-level feature extraction (edges, curves)
- Mid-level pattern recognition (shapes, strokes)
- High-level classification (digits & alphabets)

---

## 📊 Datasets Used

### 🔢 MNIST (Digits 0–9)
- 60,000 training images
- 10,000 test images
- Grayscale handwritten digits

📌 [Download here](https://www.kaggle.com/datasets/hojjatk/mnist-dataset)

---

### 🔤 EMNIST Letters (A–Z)
- 88,800+ images
- 26 classes
- Extended handwritten alphabet dataset

📌 [Download here](https://www.kaggle.com/datasets/crawford/emnist)

---

## 🏗️ Model Architecture (CNN)

- Conv2D → Feature Extraction
- MaxPooling → Dimensionality Reduction
- Batch Normalization → Training Stability
- Dropout → Overfitting Reduction
- Flatten → Vector Conversion
- Dense Layers → Classification Head
- Softmax → Output Prediction

---

## 📈 Model Performance

| Dataset | Train Accuracy | Test Accuracy | Overfitting |
|----------|---------------|---------------|-------------|
| MNIST | 99.49% | 99.28% | 0.21% |
| EMNIST | 97.05% | 93.56% | 3.49% |

📌 **Note:**
Some EMNIST letter classes (especially visually similar alphabets in the mid-range classes) show slightly lower precision and recall due to inter-class similarity (e.g., C–G, I–J, O–Q).

---

## 🏆 Key Achievements

- 🚀 Achieved **99%+ accuracy on MNIST**
- 🔤 Achieved **93%+ accuracy on EMNIST**
- 🧠 Built **dual CNN architecture system**
- ⚡ Reduced overfitting using Dropout + BatchNorm
- 📊 Improved generalization using data augmentation
- 🧪 Successfully tested on real-world handwritten images
- 🔍 Strong performance consistency across datasets

---

## 🧪 Evaluation Metrics

- Accuracy Score  
- Precision / Recall  
- F1 Score  
- Confusion Matrix  
- Training vs Validation Curves

📌 Class-wise analysis shows minor misclassification in visually similar EMNIST letters, which is expected in handwritten datasets.

---
---

## 📊 Visual Results

### 📉 Training Performance (Accuracy & Loss Curves)

**MNIST**

<img width="854" height="464" alt="MNIST Train" src="https://github.com/user-attachments/assets/10d96b9a-89c2-487f-bbda-162a356d60a4" />

---

<img width="854" height="488" alt="MNIST Loss" src="https://github.com/user-attachments/assets/822a2c0c-e8f6-43da-aea9-2401a4c1b770" />

---

**EMNIST**

<img width="1030" height="566" alt="EMNIST Gain" src="https://github.com/user-attachments/assets/aaaab604-4e19-4b26-911d-ab082f17ace8" />

---

<img width="1021" height="585" alt="EMNIST Loss" src="https://github.com/user-attachments/assets/397b1b92-5020-4821-9ba3-f433972f5d29" />


---

### 📊 Confusion Matrix - MNIST

<img width="795" height="694" alt="MNIST confusion" src="https://github.com/user-attachments/assets/988da4e2-90b6-4ee7-8f01-c9f7ee313d99" />


---

### 📊 Confusion Matrix - EMNIST

<img width="441" height="358" alt="Letter_Confusion" src="https://github.com/user-attachments/assets/4c1f1cdb-f764-4a22-8db2-7a5c5617746b" />


---

### 🧪 Sample Predictions (Real-World Testing)

Here are the few samples used for the testing

<img width="40" height="40" alt="Test_1" src="https://github.com/user-attachments/assets/3980fabf-a590-4f7b-89d0-c6ee1571af74" />

---

<img width="164" height="260" alt="Test3" src="https://github.com/user-attachments/assets/420f17b9-1992-4697-a7a2-c7288a737d52" />

---

<img width="67" height="109" alt="Test2" src="https://github.com/user-attachments/assets/b8a9167a-bef1-4e86-9b66-55c4d6ecad3a" />


---

## 🔬 Data Preprocessing Pipeline

- Grayscale normalization (0–1 scaling)
- Image resizing (28×28)
- Label encoding
- Noise reduction
- Dataset balancing (EMNIST improvements)

---

## 🔄 Data Augmentation (EMNIST)

To improve generalization:

- Rotation
- Zoom
- Width shift
- Height shift

---

## 🧪 Real-World Testing

The model was validated using:

- Handwritten test samples
- User-uploaded images
- External real-world images

### Pipeline:
1. Image upload  
2. Grayscale conversion  
3. Resize to 28×28  
4. Normalization  
5. CNN Prediction  

---

## 🛠️ Tech Stack

**Languages:**
- Python 🐍  

**Libraries:**
- TensorFlow / Keras 🤖  
- NumPy  
- Matplotlib  
- Seaborn  
- OpenCV  
- Scikit-learn  

**Environment:**
- Google Colab  
- Jupyter Notebook  

---

## 📁 Project Structure
```
Handwritten-Recognition-System/
│
├── models/
│ ├── mnist_cnn_model.keras
│ ├── emnist_cnn_model.keras
│
├── notebooks/
│ └── training_pipeline.ipynb
│
├── results/
│ ├── mnist_confusion_matrix.png
│ ├── emnist_confusion_matrix.png
│ ├── accuracy_curve.png
│ ├── loss_curve.png
│
├── samples/
│ └── real_world_tests.png
│
└── README.md
```

---

## 🔮 Future Scope

- 🌐 Deploy using Streamlit / Flask  
- 📱 Mobile app integration  
- 🎥 Real-time webcam prediction  
- 🧠 Upgrade to ResNet / EfficientNet  
- ✍️ Add drawing canvas UI  
- ⚡ TensorFlow Lite optimization  
- 🔀 Unified MNIST + EMNIST model  

---

## 👨‍💻 Author

**Datta Sai Srinivas Devulapalli**  
ML Intern | [Linkedin Profile](https://www.linkedin.com/in/sai-srinivas-devulapalli-48a592351/)

Developed as part of Machine Learning Internship at Code Alpha

---

## 📜 License

This project is licensed under the MIT License.
