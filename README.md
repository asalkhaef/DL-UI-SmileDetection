# 😊 Smile Detection using Deep Learning

## 📌 Project Overview

This project focuses on **detecting smiles in human faces** using deep learning. The dataset used is **GENKI-4K**, which contains labeled images of smiling and non-smiling faces. The goal is to train a model that can accurately classify faces based on their expressions.

## 🗂 Dataset

- **GENKI-4K Dataset**
- Two main categories:
  - `smile/`
    - Contains images of smiling faces
  - `nonsmile/`
    - Contains images of non-smiling faces

## 🛠 Preprocessing Steps

1. **Face Detection & Cropping**

   - Apply **Haar cascades** or **MTCNN** to detect and crop faces.
   - Save cropped faces into:
     - `f-smile/` → Cropped smiling faces
     - `f-nonsmile/` → Cropped non-smiling faces

2. **Data Augmentation (Optional)**
   - Techniques used:
     - Flipping
     - Rotation
     - Brightness adjustments

## 📊 Model Training

- **Deep Learning Architectures Used:**

  - MobileNet
  - AlexNet
  - VGG
  - ResNet

- **Training Details:**
  - Train each model on the processed dataset.
  - Compare performance using:
    - Accuracy
    - Precision, Recall, F1-Score
    - Confusion Matrix & ROC Curve

## 🚀 Results & Evaluation

- Model performance will be evaluated using:
  - **Accuracy**
  - **Precision, Recall, and F1-Score**
  - **Confusion Matrix & ROC Curve**
