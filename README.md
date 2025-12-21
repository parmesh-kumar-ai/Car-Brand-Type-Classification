# Car-Brand-Type-Classification
EfficientNetB0-based car brand &amp; type classification with bounding boxes
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/YOUR_USERNAME/car-brand-type-classification/blob/main/notebooks/Car_Brands_and_Type_Project.ipynb
)

# 🚗 Car Brand & Vehicle Type Classification
### A Multi-Task Computer Vision Study Using EfficientNet

---

## 📌 Overview

This repository contains a **research-oriented computer vision project** focused on the **simultaneous classification of car brand and vehicle type** from images.

The work is implemented entirely as a **Jupyter/Colab notebook** and emphasizes:
- Model architecture design
- Training and fine-tuning strategy
- Rigorous evaluation and error analysis

The project is suitable for **research review, technical interviews, and applied machine learning discussions**.

---

## 🎯 Problem Statement

Identifying:
- **Car Brand** (e.g., Hyundai, Mercedes, BMW)
- **Vehicle Type** (Sedan, Hatchback, SUV, etc.)

from images is challenging due to:
- High visual similarity across brands
- Background noise and occlusions
- Variations in lighting and viewpoint

This project explores a **multi-task learning approach** to address these challenges efficiently.

---

## 🧠 Methodology

### 🔹 Model Architecture
- Backbone: **EfficientNetB0 (ImageNet pretrained)**
- Design: **Multi-output Convolutional Neural Network**
  - Shared feature extractor
  - Separate classification heads for:
    - Car Brand
    - Vehicle Type

### 🔹 Training Strategy
- Transfer learning with frozen backbone
- Progressive fine-tuning of upper layers
- Categorical cross-entropy loss per output

---

## 📊 Evaluation & Analysis

The notebook includes **in-depth evaluation**, going beyond aggregate accuracy:

- Confusion matrices (raw and normalized)
- Per-class accuracy analysis
- Top-1, Top-3, and Top-5 accuracy
- Misclassification analysis with confidence scores

These analyses provide **interpretability and diagnostic insights** into model behavior.

---

## 🧪 Data Handling

- Image metadata handled via CSV files
- Bounding-box guided cropping for vehicle localization
- Robust handling of invalid or missing annotations

---

## 📁 Repository Structure

