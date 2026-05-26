# 🚦 Traffic Sign Recognition System

A Deep Learning project that classifies traffic signs from images using **Convolutional Neural Networks (CNNs)** and computer vision techniques. The system processes traffic sign images and predicts their categories to support intelligent transportation and autonomous driving systems.

---

## 📌 Project Overview

Traffic sign recognition is a critical task in autonomous vehicles and advanced driver assistance systems (ADAS). This project builds a deep learning model capable of recognizing different traffic signs from images using image preprocessing and CNN architectures.

The model learns visual patterns and features from traffic sign images and classifies them into multiple categories.

---

## 🎯 Objectives

- Classify traffic signs using image data
- Preprocess image datasets for training
- Build and train CNN models
- Recognize multiple traffic sign categories
- Improve prediction accuracy
- Compare different deep learning approaches

---

## 🧰 Technologies & Libraries

<div align="left">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</div>

---

## 📂 Dataset

Dataset used:

**German Traffic Sign Recognition Benchmark (GTSRB) – Kaggle**

The dataset contains:

- Traffic sign images
- Sign category labels
- Multiple traffic sign classes
- Various image sizes and conditions
- Different lighting and environmental scenarios

Examples of traffic signs:

- Speed limit signs
- Stop signs
- Yield signs
- Warning signs
- Prohibition signs

---

## ⚙️ Project Workflow

### 1. Data Collection
- Load traffic sign image dataset
- Explore classes and image distributions

### 2. Image Preprocessing

Preprocessing steps include:

- Image resizing
- Image normalization
- Noise reduction
- Label encoding
- Dataset splitting

---

## 🧠 Deep Learning Architecture

### Convolutional Neural Network (CNN)

CNN layers may include:

- Convolution layers
- ReLU activation
- MaxPooling layers
- Dropout layers
- Fully connected layers
- Softmax output layer

The CNN automatically learns image features and patterns.

---

## 🤖 Model Training

Training process:

1. Load image data
2. Preprocess and normalize images
3. Build CNN architecture
4. Train model
5. Evaluate performance
6. Predict traffic sign classes

---

## 📊 Evaluation Metrics

Performance evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report
- Validation Loss
- Training Curves

Visualization:

- Accuracy plots
- Loss curves
- Prediction examples

---

## 🔍 Covered Concepts

- Computer Vision
- Convolutional Neural Networks (CNN)
- Multi-Class Classification
- Image Processing
- Deep Learning
- TensorFlow
- Data Augmentation

---

## ⭐ Bonus Features

### Data Augmentation

Improve model generalization using:

- Rotation
- Zoom
- Horizontal shifting
- Brightness adjustment

This increases dataset diversity and reduces overfitting.

---

### Model Comparison

Compare:

**Custom CNN**

vs

**Pre-trained Models**

Examples:

- MobileNet
- ResNet
- EfficientNet

---

## 🚀 How to Run

Clone repository:

```bash
git clone https://github.com/yourusername/traffic-sign-recognition.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

or:

```bash
python main.py
```

---

## 📁 Project Structure

```bash
Traffic-Sign-Recognition/
│
├── dataset/
├── notebooks/
├── images/
├── models/
├── src/
├── saved_model/
├── main.py
├── requirements.txt
└── README.md
```

---

## 📈 Future Improvements

- Real-time traffic sign detection
- Webcam/live camera prediction
- Mobile deployment
- Object detection integration
- Faster CNN architectures

---

## 📸 System Pipeline

Images → Preprocessing → CNN Training → Feature Learning → Classification → Evaluation → Prediction

---

## 👨‍💻 Author

**Saif Fattah**

Computer Engineering Student | AI & Machine Learning Enthusiast

GitHub: https://github.com/seifmohsen324

---

⭐ If you found this project useful, consider giving it a star.
