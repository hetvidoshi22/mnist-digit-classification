# 🔢 MNIST Digit Classification using Neural Network

## 📌 Overview
This project builds a **Deep Learning model** to recognize handwritten digits (0–9) using a Neural Network trained on the **MNIST dataset**. The system learns patterns from grayscale images and predicts the correct digit with high accuracy.

Handwritten digit recognition is widely used in applications such as postal code detection, bank cheque processing, form digitization, and OCR systems.

---

## 🧠 Problem Statement
The objective of this project is to classify handwritten digit images into one of **10 classes (0–9)** using a Neural Network model.

---

## 📂 Dataset
Dataset Used: **MNIST Handwritten Digits Dataset**

### Dataset Details
- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Image Type: Grayscale
- Number of Classes: 10 (Digits 0–9)

The dataset is loaded directly using Keras.

---

## ⚙️ Technologies Used
- Python
- NumPy
- Matplotlib
- Seaborn
- TensorFlow / Keras
- OpenCV
- Jupyter Notebook

---

## 🔍 Project Workflow
1. Import required libraries  
2. Load MNIST dataset  
3. Data visualization and exploration  
4. Image normalization  
5. Neural Network model creation  
6. Model training  
7. Model evaluation  
8. Confusion matrix visualization  
9. Digit prediction  
10. Custom handwritten image testing  

---

## 🤖 Neural Network Architecture
- Input Layer: 28×28 image
- Flatten Layer
- Dense Layer (50 neurons, ReLU)
- Dense Layer (50 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

### Model Configuration
- Optimizer: Adam  
- Loss Function: Sparse Categorical Crossentropy  
- Evaluation Metric: Accuracy  

---

## 📈 Model Performance
The trained neural network achieves approximately:

✅ **97–98% accuracy** on test data.
