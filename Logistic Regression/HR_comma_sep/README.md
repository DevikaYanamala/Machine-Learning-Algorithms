# 🔢 Logistic Regression Project  

## 📌 Overview  
This project demonstrates how to use **Logistic Regression** for a classification task.  
It covers the complete workflow from loading the dataset, performing cleaning and preprocessing, to training the model and checking its accuracy.  

---

## 🗂️ Project Workflow  

1. **Data Loading**  
   - Loaded dataset into a pandas DataFrame.  

2. **Data Cleaning**  
   - Handled missing values.  
   - Renamed and adjusted column names for easier usage.  

3. **Exploratory Data Analysis (EDA)**  
   - Used pandas methods to explore the dataset.  
   - Checked feature relationships with simple plots (Matplotlib / Seaborn).  

4. **Preprocessing**  
   - Applied scaling/normalization where necessary to prepare data for the model.  

5. **Model Training**  
   - Implemented Logistic Regression using:  
     ```python
     from sklearn.linear_model import LogisticRegression
     ```  
   - Fitted the model on training data.  

6. **Evaluation**  
   - Evaluated accuracy of the model using `.score()` and predictions.  

7. **Prediction**  
   - Generated predictions for test data.  

---

## ⚙️ Tech Stack  

- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn** (for visualization)  
- **Scikit-learn** (Logistic Regression, accuracy evaluation)  
- **Jupyter Notebook**  

---

## 🚀 How to Run  

```bash
# Clone the repository
git clone https://github.com/<\DevikaYanamala>/machine-learning-algorithms.git

# Navigate into folder
cd machine-learning-algorithms/logistic_regression

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook "Logistic Regression (1).ipynb"
