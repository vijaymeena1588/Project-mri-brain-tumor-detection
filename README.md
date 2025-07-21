# Project-mri-brain-tumor-detection 🧠

A deep learning-based project that classifies brain MRI images into four categories: **Glioma**, **Meningioma**, **Pituitary**, and **No Tumor**. Built using **Convolutional Neural Networks (CNN)** and **transfer learning**, the model is deployed via **Streamlit** for real-time predictions.

---

## 📁 Dataset

- **Total Images:** 2443 MRI scans  
- **Classes:** Glioma, Meningioma, Pituitary, No Tumor  
- **Split:**
  - Training: 1695 images
  - Validation: 502 images
  - Testing: 246 images
  
---

### 🏷️ Labeling
- The images have been labeled by **medical experts** using a standardized labeling protocol.  
- Labels include both the **type of tumor** and its **location** in the brain.

### 🩺 Potential Applications
- Train machine learning models to **automatically classify brain tumors**.  
- Assist **radiologists** in diagnosing brain tumors with AI-powered tools.  
- Support the **development of new treatments** for brain tumors by aiding research and clinical trials.

---

## 🚀 Features

- Custom **CNN model** from scratch
- **Transfer learning** using pretrained models (ResNet50, MobileNetV2, etc.)
- **Data augmentation** for generalization
- Model evaluation using **accuracy**, **precision**, **recall**, and **F1-score**
- Real-time predictions using a **Streamlit web app**
- Visualization of training curves and confusion matrix

---

## 🧰 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV, NumPy, Matplotlib
- Streamlit
- Scikit-learn

---


