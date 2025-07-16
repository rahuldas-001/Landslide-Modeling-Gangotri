# 🌍 Landslide Susceptibility Modeling with Explainable AI (XAI)

This repository contains the complete pipeline for landslide susceptibility modeling using machine learning (XGBoost, MLP) and SHAP for model interpretation, as described in our paper:

**"Explainable Landslide Susceptibility Modeling using XGBoost and SHAP"**

---

## 📦 Features

- Preprocessing of landslide-related geospatial data
- Training ML models (XGBoost, MLP)
- SHAP summary and dependence plots
- Loss curves for model comparison
- Fully reproducible and well-documented

---

## 🖥️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/rahuldas-001/Landslide-Model-Gangotri.git
cd Landslide-Model-Gangotri


Overview

Landslide susceptibility modeling is a critical tool for understanding and predicting landslide-prone areas. In this project, we use ANN and XGB machine learning algorithms to build a susceptibility model based on various causative factors influencing landslides in the Upper Bhagirathi basin. The model is evaluated using key performance metrics like precision, recall, and accuracy to ensure robustness. All the data used in the modelling can be accessed from the drive link : https://drive.google.com/drive/folders/1ROxOoe7Q6TK48Qrg1my-8xIfvZ2cq2B3?usp=drive_link 

Key Features

Data Preparation:

Process geospatial data and compile various landslide causative factors such as slope, aspect, land use, soil type, and rainfall.
Multicollinearity Analysis: Perform multicollinearity analysis using Pearson correlation to identify and remove highly correlated variables, improving model performance.

Modeling Algorithms:

Artificial Neural Networks (ANN) for complex, nonlinear pattern recognition.
Extreme Gradient Boosting (XGB) for gradient-boosted decision trees, offering high accuracy and performance.
Accuracy Assessment: Evaluate model performance using precision, recall, accuracy, and other relevant metrics for reliable landslide susceptibility prediction
![image](https://github.com/user-attachments/assets/292bd832-0c96-4133-92c8-5455ff000301)


To visualize the code and its output users can also go through this Google Collab Link : https://colab.research.google.com/drive/1hRV8fEqgZ_yETxOlfJbp7SwTUQR7fmco?authuser=4

