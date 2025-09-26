# 🔢 Handwritten Digit Recognition with KNN

This project demonstrates how to use the **K-Nearest Neighbors (KNN) algorithm** to classify handwritten digits from the **scikit-learn Digits dataset**. It walks through data preprocessing, model training, evaluation, and visualization of results.

---

## 📊 Workflow
1. Load the digits dataset using `sklearn.datasets.load_digits()`.  
2. Explore the dataset and prepare a pandas DataFrame.  
3. Split the data into training and testing sets (80/20).  
4. Train a **KNN classifier** (`n_neighbors=2`).  
5. Evaluate the model using accuracy and confusion matrix (~99% accuracy).  
6. Visualize misclassifications and the confusion matrix.  

---

## 🛠️ Tech Stack
- Python 3.12+  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🚀 Run the Project
```bash
git clone https://github.com/your-username/knn-digit-classifier.git && cd knn-digit-classifier && pip install -r requirements.txt && jupyter notebook "KNN exercise.ipynb"

