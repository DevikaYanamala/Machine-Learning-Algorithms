📘 Project Description

This project demonstrates the implementation of a Decision Tree Classifier using the Titanic dataset to predict passenger survival.
It covers the entire pipeline — from data preprocessing and feature engineering to model training and evaluation.

Key highlights:

Data cleaning and handling missing values.

Feature selection and categorical encoding.

Splitting dataset into training and testing sets.

Building and training a Decision Tree Classifier using scikit-learn.

Evaluating the model’s accuracy (achieving ~79%).



# 🚢 Titanic Survival Prediction with Decision Tree

This repository contains a machine learning project that applies a **Decision Tree Classifier** to predict survival on the Titanic dataset.  
It demonstrates end-to-end model building: data preprocessing, feature engineering, training, and evaluation.

---

## 📊 Dataset
The dataset used is the famous **Titanic dataset**, which contains passenger details such as:
- Passenger class (Pclass)  
- Sex  
- Age  
- Fare  
- Survival status  

---

## ⚙️ Steps in the Project
1. **Data Preprocessing**
   - Removed irrelevant features (`PassengerId`, `Name`, `Ticket`, `Cabin`, etc.).
   - Filled missing `Age` values with the mean.
   - Converted categorical values (e.g., `Sex`) into numerical format.

2. **Feature Engineering**
   - Selected relevant features: `Pclass`, `Sex`, `Age`, `Fare`.
   - Target variable: `Survived`.

3. **Model Training**
   - Split dataset into training and testing sets (80/20 split).
   - Used `DecisionTreeClassifier` from `scikit-learn`.

4. **Evaluation**
   - Achieved an accuracy of **~79%** on the test set.

---

## 🛠️ Tech Stack
- **pandas** – Data manipulation  
- **matplotlib** – Visualization  
- **scikit-learn** – Machine learning (Decision Tree, train-test split)  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/DevikaYanamala/Machine-Learning-Algorithms.git
   cd Machine-Learning-Algorithms
   pip install -r requirements.txt
   jupyter notebook "Decision Tree.ipynb"

