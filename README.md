# Pneumonia-detectionu-CNN-
A deep learning model that detects pneumonia from chest X-ray images using CNNs. It uses preprocessing, data augmentation, regularization, and early stopping to improve accuracy and reduce overfitting.
# 🩺 Pneumonia Detection using CNN

This project is a deep learning-based image classification system to detect **Pneumonia** from chest X-ray images using Convolutional Neural Networks (CNNs).

## 🧠 Model Architecture

The CNN model is built with the following configuration:

- **5 Convolutional Layers**  
  - Filters: 16, 32, 64, 128, 128  
  - Activation: ReLU  
  - Each Conv2D layer followed by MaxPooling  
  - Regularization: L2 (0.001)  
  - Dropout: 0.3 to prevent overfitting

- **3 Dense Layers**  
  - First Dense: 256 neurons (Dropout = 0.5)  
  - Second Dense: 512 neurons  
  - Final Output Layer: 1 neuron (Sigmoid for binary classification)

## 🔧 Techniques Used

- 📦 **Data Augmentation** (rotation, flip, zoom)
- 🔒 **L2 Regularization**
- 🧯 **Dropout Regularization**
- 🧪 **Early Stopping**
- 📊 **Model Evaluation with Accuracy & Loss curves**

## 🛠️ Tech Stack

- Python 🐍
- TensorFlow + Keras
- NumPy
- Matplotlib
- ImageDataGenerator for training/validation split

## 📁 Dataset--https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

Chest X-ray dataset containing images classified as **NORMAL** or **PNEUMONIA**.

## 🚀 How to Run

1. Clone the repo  
2. Load the dataset into the correct folder structure  
3. Train the model using `model.fit()`  
4. Evaluate using test data or real-time predictions

---

> 🔬 *This project demonstrates how deep learning can assist in medical imaging to support faster and more reliable pneumonia diagnosis.*

