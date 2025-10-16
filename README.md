# 🧠 Brain Tumor Classification Using Ensemble CNN Models

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13-orange.svg)](https://www.tensorflow.org/) 
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This project focuses on **classifying brain tumors from MRI scans** using an **ensemble of deep learning models** for high accuracy. It combines **VGG16** and **ResNet** architectures with **transfer learning and ensembling**.

---

## 🚀 Features
- **Data Preprocessing & Augmentation:** Handles MRI images to improve model learning.  
- **Ensemble Modeling:** Combines multiple CNN models for better generalization and accuracy.  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix.  
- **Real-World Application:** Early detection of brain tumors to support healthcare professionals.

---

## 📂 Dataset
Uses publicly available MRI brain tumor datasets.  
Images are **preprocessed, resized, normalized, and augmented** for optimal performance.

**Tumor Classes:**

| Class      | Description                  |
|------------|------------------------------|
| Glioma     | Most common brain tumor type |
| Meningioma | Tumor originating from meninges |
| Pituitary  | Tumor in the pituitary gland |
| No Tumor   | Normal brain MRI             |

---

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/brain-tumor-classification.git
cd brain-tumor-classification

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
