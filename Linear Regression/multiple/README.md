This project demonstrates Multiple Linear Regression for predictive modeling. Unlike simple regression (single feature), here multiple independent features are used to predict the dependent variable.

Key steps performed:

📂 Loaded dataset into pandas DataFrame

🧹 Data cleaning (handling missing values & renaming columns)

📊 Exploratory data analysis and visualization

⚖️ Applied feature scaling where needed

🤖 Built a Multiple Linear Regression model using sklearn.linear_model.LinearRegression

📈 Evaluated model performance with metrics like R² score and cross-validation

🔮 Made predictions for new input values




# 📊 Multiple Linear Regression Project  

## 📌 Overview  
This project applies **Multiple Linear Regression** to a dataset with several independent variables.  
The goal is to demonstrate how multiple features can be combined to predict a target variable effectively.  

---

## 🗂️ Project Workflow  

1. **Data Loading**  
   - Imported dataset using **pandas**  

2. **Data Cleaning**  
   - Checked for missing values  
   - Renamed/modified columns for easier handling  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized relationships between independent and dependent variables  
   - Identified correlations  

4. **Feature Engineering & Preprocessing**  
   - Applied scaling where needed  
   - Prepared data for model training  

5. **Model Training**  
   - Built a **Multiple Linear Regression** model using `sklearn.linear_model.LinearRegression`  
   - Trained on independent variables (X) to predict target (y)  

6. **Evaluation**  
   - Measured model accuracy with **R² score**  
   - Used **cross-validation** for performance consistency  

7. **Prediction**  
   - Generated predictions for unseen data  

---

## ⚙️ Tech Stack  

- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn** (for visualization)
- **Scikit-learn** (Linear Regression, cross-validation) 
- **Jupyter Notebook**  

---

## 🚀 How to Run  

```bash
# Clone the repository
git clone https://github.com/<DevikaYanamala>/machine-learning-algorithms.git

# Go to project folder
cd machine-learning-algorithms/linear_regression/multiple

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook "Linear Regression multiple.ipynb"
