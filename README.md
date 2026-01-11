# 🍎 AgriVision – Fruit Image Classification using Deep Learning

## 📌 Project Overview
AgriVision is a computer vision project that classifies fruit images into multiple categories using transfer learning. The system is designed for automated agricultural quality inspection and smart fruit sorting.

---

## 🎯 Objective
- Classify fruit images into 10 different categories
- Apply transfer learning using a pre-trained CNN
- Evaluate performance using accuracy, precision, recall, F1-score
- Analyze model errors and misclassifications
- Fine-tune the model for improved accuracy

---

## 🗂 Dataset
- Image-based multi-class fruit dataset
- Organized into `train`, `validation`, and `test` folders
- Each folder contains class-wise subdirectories

---

## 🧠 Model & Methodology
- **Base Model:** MobileNetV2 (pre-trained on ImageNet)
- **Why MobileNetV2?**
  - Lightweight and efficient
  - Performs well on small datasets
  - Fast inference for real-time deployment
- **Training Strategy:**
  1. Freeze base model and train classification head
  2. Evaluate base model
  3. Fine-tune top layers with low learning rate (1e-5)

---

## 📊 Results

### Quantitative Metrics
- Test Accuracy (Base Model): XX%
- Test Accuracy (Fine-tuned Model): XX%

### Evaluation Metrics
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Visualizations
- Training vs Validation Accuracy & Loss
- Confusion Matrix
- Misclassified Image Samples

---

## 🚀 Deployment / Inference
The trained model can predict fruit classes from new images and is suitable for real-time agricultural applications.

---

## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy, Pandas
- Matplotlib, Seaborn
- Google Colab

---

## 📁 Repository Structure

