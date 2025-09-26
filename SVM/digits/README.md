📌 Project Description

This notebook applies a Support Vector Machine (SVM) classifier to the Digits dataset from scikit-learn.
The dataset consists of 8×8 images of handwritten digits (0–9). Each image is represented as a flattened 64-feature vector.

Steps included:

Load dataset (load_digits)

Create a DataFrame for exploration

Train-test split (80/20)

Train different SVM models with varying kernels (rbf, linear) and parameters (C)

Evaluate accuracy (achieved ~99.1% test accuracy with SVC(C=10))

# 🔢 SVM Classifier on Digits Dataset

This repository contains a professional practice notebook implementing **Support Vector Machines (SVM)** on the **scikit-learn Digits dataset**.

---

## 📊 Project Overview
The Digits dataset contains **1,797 samples of handwritten digits (0–9)**, each represented as:
- **64 features** (8×8 grayscale pixel values)  
- A target label (digit 0–9)  

The goal is to classify handwritten digits using SVM with different kernels and parameters.

---

## ⚙️ Features
- Dataset exploration with pandas  
- Train-test split for model evaluation  
- Model training using `sklearn.svm.SVC`  
- Testing different kernels (`rbf`, `linear`)  
- Hyperparameter tuning with parameter `C`  
- Achieved **~99% accuracy** on test data  

---

## 🚀 Tech Stack
- **Python 3**  
- **pandas** for data handling  
- **matplotlib** for visualization  
- **scikit-learn** for dataset and SVM  

---


---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DevikaYanamala/Machine-Learning-Algorithms.git
   cd Machine-Learning-Algorithms
   pip install -r requirements.txt
   jupyter notebook "SVM Pro.ipynb"



