# CodeAlpha_EmotionRecognition

This project focuses on recognizing human emotions from speech audio using Deep Learning and Speech Signal Processing techniques.

The model analyzes speech recordings and predicts the emotional state of a speaker based on extracted audio features.

---

# Emotion Recognition from Speech using Deep Learning

A Deep Learning project that identifies emotions from speech audio using advanced feature extraction, data augmentation, and neural network classification.

---

# 🎯 Project Overview

This project applies speech signal processing and Deep Learning techniques to classify emotions from audio recordings.

## Emotions Covered

* Angry
* Calm
* Disgust
* Fearful
* Happy
* Neutral
* Sad
* Surprised

## Techniques Used

* Audio Feature Extraction
* Data Augmentation
* Deep Neural Networks (DNN)
* Batch Normalization
* Dropout Regularization
* Early Stopping

---

# 🚀 Key Achievements

✅ Improved model accuracy from **29.51% → 77.17%**

✅ Expanded dataset from **1,440 → 5,760 audio samples** using audio augmentation

✅ Achieved **77.17% Accuracy**

✅ Achieved **77.82% Precision**

✅ Achieved **77.17% Recall**

✅ Achieved **77.14% F1 Score**

✅ Reduced overfitting using BatchNormalization and Dropout layers

---

# 📊 Results

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 77.17% |
| Precision | 77.82% |
| Recall    | 77.17% |
| F1 Score  | 77.14% |

---

# 📈 Evaluation Metrics

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

# 🎤 Speech Emotion Recognition

## Initial Model Performance

* Used only basic MFCC features
* No data augmentation
* Small dataset size (1,440 samples)
* Basic neural network architecture
* Lower classification performance

### Initial Results

* Accuracy: **29.51%**
* Precision: **20.87%**
* Recall: **29.51%**
* F1 Score: **23.28%**

---

## Optimized Model Performance

✅ Applied Noise Injection Augmentation

✅ Applied Pitch Shifting Augmentation

✅ Applied Time Stretching Augmentation

✅ Increased dataset size from **1,440 → 5,760 samples**

✅ Extracted multiple speech features

✅ Applied Feature Scaling using StandardScaler

✅ Added BatchNormalization layers

✅ Added Dropout layers

✅ Used EarlyStopping to prevent overfitting

✅ Improved accuracy from **29.51% → 77.17%**

---

# 🎯 Final Model Performance

* Accuracy: **77.17%**
* Precision: **77.82%**
* Recall: **77.17%**
* F1 Score: **77.14%**

## Confusion Matrix

<img width="696" height="595" alt="Screenshot 2026-05-30 221358" src="https://github.com/user-attachments/assets/bb91ae2d-2c7d-4c11-8330-ede45fa5bf45" />


---

# 📈 Training Accuracy Graph

<img width="581" height="394" alt="Screenshot 2026-05-30 221728" src="https://github.com/user-attachments/assets/58b408ff-0740-4c1f-9a34-93672f740b51" />


---

# 📉 Training Loss Graph

<img width="579" height="390" alt="Screenshot 2026-05-30 221735" src="https://github.com/user-attachments/assets/6a75aee4-0cf7-400b-948e-3d251de5d180" />


---

# 🧠 Deep Learning Architecture

The model was developed using TensorFlow and Keras.

### Architecture

* Dense Layer (512 Neurons)
* BatchNormalization
* Dropout
* Dense Layer (256 Neurons)
* BatchNormalization
* Dropout
* Output Layer (8 Emotion Classes)

### Activation Functions

* ReLU
* Softmax

### Optimizer

* Adam Optimizer

### Loss Function

* Categorical Crossentropy

---

# 🎵 Audio Features Extracted

The following audio features were extracted from each speech recording:

* MFCC (Mel Frequency Cepstral Coefficients)
* Chroma Features
* Mel Spectrogram
* RMS Energy
* Spectral Centroid
* Spectral Bandwidth
* Spectral Contrast
* Spectral Rolloff
* Tonnetz Features
* Zero Crossing Rate (ZCR)

These features help the model capture emotional patterns from speech signals.

---

# 🛠️ Technical Stack

## Programming Language

* Python

## Environment

* Google Colab
* Jupyter Notebook

## Libraries Used

* TensorFlow
* Keras
* NumPy
* Pandas
* Librosa
* Matplotlib
* Scikit-learn
* Joblib

---

# 🧠 Deep Learning Techniques Used

* Audio Feature Extraction
* Data Augmentation
* Feature Scaling
* Label Encoding
* Deep Neural Networks
* Batch Normalization
* Dropout Regularization
* Early Stopping
* Performance Evaluation

---

# 🔍 Data Preprocessing

The following preprocessing steps were performed:

* Audio Loading
* Feature Extraction
* Noise Injection
* Pitch Shifting
* Time Stretching
* Feature Scaling
* Label Encoding
* Train-Test Split

These preprocessing techniques significantly improved model performance and generalization capability.

---

# 🚀 Quick Start

## Installation

```bash
pip install tensorflow librosa numpy pandas matplotlib scikit-learn joblib
```

▶️ Run the Project

Open the notebook in Google Colab or Jupyter Notebook

Download the RAVDESS dataset

Update the dataset path

Run all cells sequentially

Train the model and save the generated files

---

# 📁 Project Structure

Task2_Emotion_Recognition/
│
├── EmotionRecognition.ipynb
├── README.md
├── requirements.txt
│
├── models/
│   ├── emotion_model.keras
│   └── label_encoder.pkl
│
├── results/
│   ├── confusion_matrix.png
│   ├── accuracy_graph.png
│   └── loss_graph.png
│
└── dataset/
└── dataset_link.txt

---

# 📚 Dataset Used

The dataset used in this project was sourced from the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) dataset.

# Dataset

* RAVDESS Emotional Speech Dataset

## Dataset Information

* 24 Professional Actors
* 12 Male Actors
* 12 Female Actors
* 8 Emotion Categories
* High Quality Audio Recordings

## Dataset Link

* RAVDESS Dataset

  [Download Here](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

  

# Note

The dataset is not included in this repository due to its large size.

Please download it using the link above before running the notebook.

---

# ⚙️ Deep Learning Workflow

* Data Collection
* Audio Loading
* Feature Extraction
* Data Augmentation
* Feature Scaling
* Label Encoding
* Train-Test Split
* Model Building
* Model Training
* Prediction
* Model Evaluation

---

# 📈 Future Improvements

* Implement CNN Architecture
* Implement CNN + LSTM Hybrid Models
* Real-Time Emotion Detection
* Live Microphone Input Prediction
* Web Application Deployment
* Mobile Application Integration

---

# 👤 Author

Datta Sai Srinivas Devulapalli

ML Intern | https://www.linkedin.com/in/sai-srinivas-devulapalli-48a592351/

Developed as part of Machine Learning Internship at Code Alpha

---

# 📄 License

This project is open source and available under the MIT License.

