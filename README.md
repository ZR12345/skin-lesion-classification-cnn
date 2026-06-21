# Skin Lesion Classification using CNN

Deep learning-based skin lesion classification using Convolutional Neural Networks (CNNs) on the HAM10000 dataset for automated skin cancer detection and diagnosis support.

## Overview

Skin cancer is one of the most common forms of cancer worldwide, making early detection crucial for effective treatment. This project implements a deep learning-based image classification system that analyzes dermoscopic images and predicts the type of skin lesion using Convolutional Neural Networks (CNNs).

The model is trained on the HAM10000 dataset, a large collection of multi-source dermatoscopic images representing common pigmented skin lesions.

## Features

* Image preprocessing and normalization
* Data visualization and exploratory analysis
* CNN-based skin lesion classification
* Model training and validation
* Performance evaluation using classification metrics
* Prediction of lesion categories from dermoscopic images

## Dataset

This project uses the **HAM10000 (Human Against Machine with 10,000 Training Images)** dataset.

The dataset contains dermoscopic images belonging to multiple skin lesion categories, including:

* Melanocytic nevi (nv)
* Melanoma (mel)
* Benign keratosis-like lesions (bkl)
* Basal cell carcinoma (bcc)
* Actinic keratoses (akiec)
* Vascular lesions (vasc)
* Dermatofibroma (df)

Dataset source:
https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

> Note: The dataset is not included in this repository due to its size and licensing requirements.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
skin-lesion-classification-cnn/
│
├── Skin_Cancer_Detection.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── data/ (not included)
```

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/skin-lesion-classification-cnn.git
cd skin-lesion-classification-cnn
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Download the HAM10000 dataset.
2. Place the dataset in the appropriate directory.
3. Open the notebook:

```bash
jupyter notebook Skin_Cancer_Detection.ipynb
```

4. Run all cells to preprocess data, train the model, and evaluate performance.

## Results

The project demonstrates the application of deep learning techniques for automated skin lesion classification. Performance can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Future Improvements

* Transfer Learning using EfficientNet or ResNet
* Model deployment using Flask or Streamlit
* Hyperparameter optimization
* Explainable AI techniques (Grad-CAM)
* Real-time image prediction interface

## Disclaimer

This project is intended for educational and research purposes only. It should not be used as a substitute for professional medical diagnosis.
