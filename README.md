# 🧠 Breast Cancer Histopathology Image Classification

An end-to-end **Deep Learning-based medical image classification system** that classifies histopathological breast cancer images into **8 tumor subtypes** using advanced CNN architectures like EfficientNet and ResNet.

---

## 🚀 Project Overview

This project leverages **deep learning and computer vision** to automate the classification of breast cancer histopathology images, assisting in early diagnosis and reducing manual effort in pathology workflows.

- 🧬 Multi-class classification (8 tumor types)
- 🧠 Deep learning models (EfficientNet, ResNet)
- 🌐 Web interface for real-time prediction
- 📊 Performance evaluation with accuracy, precision, recall, F1-score

---

## 📊 Dataset Details

- **Dataset Name:** BreakHis (Breast Cancer Histopathological Database)
- **Source:** Public medical dataset (commonly available via Kaggle / research datasets)
- **Total Images:** ~7,900+ images  
- **Classes:** 8 tumor subtypes

### 📌 Classes:

- adenosis  
- ductal_carcinoma  
- fibroadenoma  
- lobular_carcinoma  
- mucinous_carcinoma  
- papillary_carcinoma  
- phyllodes_tumor  
- tubular_adenoma  

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Deep Learning:** PyTorch  
- **Computer Vision:** torchvision  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Web Framework:** Flask  
- **Frontend:** HTML, CSS  

---

## 🌐 Web Application

A Flask-based web interface allows users to:

- Upload histopathology images
- Get real-time predictions
- View confidence scores
- Visualize results with UI feedback

---

## 🧪 Training Pipeline

1. Load dataset and apply transformations
2. Perform train/validation/test split
3. Train model using transfer learning
4. Fine-tune model for better accuracy
5. Evaluate using multiple metrics
6. Save trained model (`model3.pth`)

---

## 📊 Model Training

The model was trained using **EfficientNet-B0** (can be extended to B1/B2 variants for improved performance).

- 🖼️ Input Image Size: **224 × 224**
- ⚙️ Optimizer: **Adam**
- 📉 Loss Function: **CrossEntropyLoss**
- 📈 Validation Accuracy: **~88%**
