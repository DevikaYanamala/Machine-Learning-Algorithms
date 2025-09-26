# 🍷 Wine Classification with Naive Bayes

This project demonstrates the use of **Naive Bayes (GaussianNB)** to classify wine samples from the **scikit-learn Wine dataset**.  
It covers dataset exploration, preprocessing, model training, evaluation, and making predictions on new data.

---

## 📊 Workflow
1. Load the Wine dataset using `sklearn.datasets.load_wine()`.  
2. Convert the dataset into a pandas DataFrame for easy exploration.  
3. Explore features such as alcohol, flavanoids, color intensity, proline, etc.  
4. Split the dataset into training and testing sets (80/20).  
5. Train a **Gaussian Naive Bayes classifier** on the training data.  
6. Evaluate the model → achieved **100% accuracy** on the test set.  
7. Predict wine class for custom feature input.  

---

## 🛠️ Tech Stack
- Python 3.12+  
- pandas – Data handling  
- scikit-learn – Dataset, GaussianNB, train/test split  

---

## 🚀 Run the Project
```bash
git clone https://github.com/DevikaYanamala/Machine-Learning-Algorithms.git && cd Machine-Learning-Algorithms && pip install -r requirements.txt && jupyter notebook "Naive bayes wine.ipynb"

