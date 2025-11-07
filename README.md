# Lung-Cancer-Detection-using-Deep-Learning-Models
Lung Cancer Detection using Deep Learning (CNN + Transfer Learning) — A deep learning project that classifies lung CT scan images into Normal, Benign, and Malignant categories using models like MobileNetV2, InceptionV3, and ResNet50 for early cancer detection and diagnosis assistance.

# 🩺 Lung Cancer Detection using Deep Learning

This project applies **deep learning** techniques to detect and classify **lung cancer** from **CT scan images**.  
Using transfer learning models such as **MobileNetV2**, **InceptionV3**, and **ResNet50**, it predicts whether a scan is **Normal**, **Benign**, or **Malignant**, supporting early detection and diagnosis.

---

## 🚀 Project Overview
Lung cancer is one of the leading causes of cancer deaths worldwide.  
Early detection significantly improves survival rates.  
This project leverages **Convolutional Neural Networks (CNNs)** with **transfer learning** to automate image classification for lung cancer diagnosis.

---

## 🧠 Models Used
- **MobileNetV2** — Lightweight, efficient for real-time use.  
- **InceptionV3** — High-performing deep CNN architecture for image classification.  
- **ResNet50** — Residual connections help prevent vanishing gradients in deeper networks.  

Each model was fine-tuned on the **IQ-OTHNCCD Lung Cancer Dataset** from Kaggle.

---

## 📂 Dataset
**Dataset Name:** The IQ-OTHNCCD Lung Cancer Dataset  
**Path Used:**  

**Classes:**
- `Normal`
- `Benign`
- `Malignant`

The dataset contains CT scan images of lungs for model training and evaluation.

---

## ⚙️ Project Pipeline
1. **Data Preprocessing**
   - Image resizing and normalization
   - Data augmentation (rotation, zoom, flip)
   - Train-test split

2. **Model Building**
   - Transfer learning using pre-trained CNNs (MobileNetV2, InceptionV3, ResNet50)
   - Added custom dense layers for classification
   - Compiled using Adam optimizer and categorical cross-entropy loss

3. **Training & Evaluation**
   - Model training on GPU-enabled environment
   - Metrics: Accuracy, Precision, Recall, F1-Score
   - Visualization using confusion matrix and accuracy/loss plots

4. **Prediction**
   - Single image prediction function using trained models
   - Outputs predicted class and confidence score

---

## 📊 Results
- Achieved high accuracy across all three models.
- **MobileNetV2** performed best in terms of efficiency and inference speed.
- Visualization includes:
  - Confusion Matrix
  - Training vs Validation Accuracy
  - Training vs Validation Loss

---

## 🧩 Technologies Used
- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy / Pandas / Matplotlib**
- **Google Colab**

---
