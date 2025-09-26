# 📧 SMS Spam Classification with Naive Bayes

This project demonstrates how to classify SMS messages as **spam** or **ham (not spam)** using the **Naive Bayes algorithm**.  
It includes data preprocessing, feature extraction with `CountVectorizer`, model training, evaluation, and predictions on custom messages.

---

## 📊 Workflow
1. Load the SMS dataset (`spam.csv`) containing labeled messages (ham/spam).  
2. Preprocess the dataset by mapping categories to numeric values.  
3. Split the dataset into training and test sets (80/20).  
4. Convert text data into feature vectors using **CountVectorizer**.  
5. Train a **Multinomial Naive Bayes classifier**.  
6. Evaluate the model → achieved **~98.5% accuracy**.  
7. Test with custom messages to predict spam/ham.  
8. Build a **Pipeline** combining vectorization and classification for cleaner code.  

---

## 🛠️ Tech Stack
- Python 3.12+  
- pandas – Data handling  
- scikit-learn – CountVectorizer, MultinomialNB, train/test split, Pipeline  

---

## 🚀 Run the Project
```bash
git clone https://github.com/DevikaYanamala/Machine-Learning-Algorithms.git && cd Machine-Learning-Algorithms && pip install -r requirements.txt && jupyter notebook "Naive bayes spam.ipynb"
