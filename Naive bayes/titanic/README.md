# 🚢 Titanic Survival Prediction with Naive Bayes

This project applies the **Naive Bayes Classifier** to predict passenger survival on the Titanic dataset.  
It demonstrates an end-to-end machine learning workflow — data preprocessing, feature selection, model training, and evaluation.

---

## 📊 Workflow
1. Load and preprocess the Titanic dataset.  
2. Remove irrelevant features (e.g., PassengerId, Name, Ticket, Cabin, Embarked).  
3. Handle missing values (e.g., fill `Age` with the mean).  
4. Convert categorical variables (`Sex`) into numeric form.  
5. Select relevant features (`Pclass`, `Sex`, `Age`, `Fare`) and define the target (`Survived`).  
6. Split dataset into training and testing sets (80/20).  
7. Train a **Gaussian Naive Bayes classifier**.  
8. Evaluate the model (accuracy ~75%).  

---

## 🛠️ Tech Stack
- Python 3.12+  
- pandas – Data manipulation  
- scikit-learn – Naive Bayes, train/test split, preprocessing  

---

## 🚀 Run the Project
```bash
git clone https://github.com/DevikaYanamala/Machine-Learning-Algorithms.git && cd Machine-Learning-Algorithms && pip install -r requirements.txt && jupyter notebook "Naive Bayes.ipynb"

