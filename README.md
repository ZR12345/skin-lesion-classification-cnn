# Skin Lesion Classification using Deep Learning

A deep learning-based skin lesion classification system developed using TensorFlow and Keras for automated skin cancer detection on the HAM10000 dataset.

## Project Overview

Skin cancer is among the most prevalent forms of cancer worldwide, making early diagnosis crucial for effective treatment. This project leverages deep learning techniques to classify dermoscopic skin lesion images into multiple diagnostic categories.

The proposed architecture incorporates:

* Residual Learning Blocks
* Convolutional Block Attention Module (CBAM)
* Multi-Head Self-Attention
* Focal Loss for Class Imbalance Handling
* Data Augmentation
* Stratified Dataset Splitting
* Model Checkpointing and Early Stopping

These enhancements improve feature extraction, attention to diagnostically relevant regions, and robustness against class imbalance.

---

## Dataset

The project uses the HAM10000 (Human Against Machine with 10,000 Training Images) dataset containing dermoscopic images of seven skin lesion categories:

| Class | Description                   |
| ----- | ----------------------------- |
| nv    | Melanocytic Nevi              |
| mel   | Melanoma                      |
| bkl   | Benign Keratosis-like Lesions |
| bcc   | Basal Cell Carcinoma          |
| akiec | Actinic Keratoses             |
| vasc  | Vascular Lesions              |
| df    | Dermatofibroma                |

Dataset Link:
https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

---

## Model Architecture

The model combines convolutional feature extraction with attention mechanisms:

Input Image
↓
Convolution Layers
↓
Residual Blocks
↓
CBAM Attention Module
↓
Multi-Head Self Attention
↓
Global Feature Aggregation
↓
Dense Classification Layers
↓
7-Class Skin Lesion Prediction

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Repository Structure

```text
skin-lesion-classification-cnn/
│
├── Skin_Cancer_Detection.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
├── results/
│   ├── dataset_analysis/
│   ├── training/
│   ├── evaluation/
│   ├── model/
│   └── sample_predictions/
│
└── assets/
```

## Results

### Dataset Distribution

(Add screenshot)

### Training Accuracy

(Add screenshot)

### Training Loss

(Add screenshot)

### Confusion Matrix

(Add screenshot)

### ROC Curve

(Add screenshot)

### Sample Predictions

(Add screenshot)

---

## Key Features

✔ Deep CNN Architecture

✔ Residual Connections

✔ CBAM Attention Mechanism

✔ Multi-Head Self-Attention

✔ Focal Loss for Class Imbalance

✔ Early Stopping & Checkpointing

✔ Multi-Class Skin Lesion Classification

---

## Future Work

* EfficientNet-based Transfer Learning
* Grad-CAM Visualization
* Web-based Deployment using Streamlit
* Mobile Application Integration
* Clinical Decision Support Integration

---

## Disclaimer

This project is intended for educational and research purposes only and should not be used as a substitute for professional medical diagnosis.

---

Author: Zaed Rizwan
