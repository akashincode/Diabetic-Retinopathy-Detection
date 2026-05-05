# Diabetic Retinopathy Detection

A deep learning project to detect **Diabetic Retinopathy (DR)** in retinal fundus images using transfer learning.

**Owner:** Akash Adhikary

---

## Overview

This project implements a binary classification pipeline (No-DR vs DR) on the APTOS 2019 dataset, comparing EfficientNetB0 and ResNet50 with CLAHE-enhanced preprocessing.

**Dataset:** [APTOS 2019 Blindness Detection — Kaggle](https://www.kaggle.com/datasets/mariaherrerot/aptos2019)

---

## Project Structure

```
├── Diabetic_Retinopathy_Detection.ipynb   # Main notebook
└── README.md
```

---

## Pipeline

1. Setup & Imports
2. Dataset Download & Inspection
3. EDA — Class Distribution, Resolution, Intensity
4. Multivariate Analysis
5. Binary Label Mapping & Balanced Subset (~1200 images)
6. Augmentation Pipeline (Crop, CLAHE, Flips)
7. Baseline CNN
8. Transfer Learning — EfficientNetB0
9. Transfer Learning — ResNet50
10. Comparative Evaluation (ROC, AUC, Confusion Matrix)
11. Multi-class Extension Stub

---

## Tech Stack

`TensorFlow` · `Keras` · `OpenCV` · `scikit-learn` · `Plotly` · `Seaborn`

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. A Kaggle account is required for dataset download via `kagglehub`
