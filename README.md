# 🚗 Car Brand & Vehicle Type Classification
**A Multi-Task Computer Vision Study using EfficientNetB0-based car brand and type classification with bounding boxes**
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/YOUR_USERNAME/car-brand-type-classification/blob/main/notebooks/Car_Brands_and_Type_Project.ipynb
)

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

These analyses provide **interpretability and diagnostic insights** into model behavior.

---

## 📊 Dashboard Preview

### Sentiment Analysis and SEBI Fraud Risk Analysis Module
![Preview of Confusion Matrix (raw and Normalized)](ConfusionMatrices.png)

![Preview of Model Accuracy over Brand, Type and Loss](AccuracyOverBrandTypeAndLoss.png)

---

## 🧪 Data Handling

- Image metadata handled via CSV files
- Bounding-box guided cropping for vehicle localization

---

## 📁 Input Car Image Data

- There are two types of datasets used: (1) train_data and (2) test_data. The folder train_data contains 478 car images with subfolders (a) Convertible, (b) Hatchback and (c) Sedan. The test_data folder contain only 54 car images.
- There is one CSV file which gives a clear information about brands and types of the cars.
- 

---

## ▶️ How to Run
### Open the notebook or click on Google Colab
[Car Brand & Type Classification Notebook] (CarBrand&TypeClassification.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/YOUR_USERNAME/car-brand-type-classification/blob/main/notebooks/Car_Brands_and_Type_Project.ipynb
)

---

## 🧩 Technology Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy and Pandas
- Scikit-learn
- Matplotlib and Seaborn

---

## 🚀 Applications
- Automotive Analytics
- Intelligent transport systems
- Vehicle inspection platforms
- AI-driven automotive startups
- Research and benchmarking

---

## 🌐 Google Drive Link
👉 **Check out the link here for more details:**  
🔗 https://drive.google.com/drive/folders/1qgUuWCbQyLyzA7KEEqHnmphKa1ypvF7F?usp=sharing

---

## 👤 About Author
### Parmesh Kumar
MBA (Data Science) -IIM Visakhapatnam

MSc (Physics) - IIT Kharagpur

This project is created and maintained by **Parmesh Kumar**.


📄 Read more about the author here:  
👉 [Author.md](Author.md)

