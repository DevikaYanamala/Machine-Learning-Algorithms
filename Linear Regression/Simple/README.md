# 🇨🇦 Canada Per Capita Income Prediction - Linear Regression  

This repository contains a simple **Linear Regression model** that predicts **Canada's per capita income** based on historical data.  

---

## 📂 Project Overview  
The goal of this project is to apply **supervised machine learning** (linear regression) on a simple dataset and understand how regression can be used to predict future values.  

### Steps in the Project:
1. **Load Dataset**  
   - Used `pandas` to read CSV file containing year-wise per capita income data.  

2. **Data Preprocessing**  
   - Cleaned column names for easier handling.  

3. **Data Visualization**  
   - Used `matplotlib` to plot scatter plots for year vs. income.  

4. **Model Building**  
   - Trained a **Linear Regression model** from `sklearn.linear_model`.  
   - Plotted regression line over scatter plot.  

5. **Prediction**  
   - Predicted income values for specific years (e.g., 2020).  

---

## 🚀 How to Run  

```bash
# Clone repository
git clone https://github.com/DevikaYanamala/Machine-Learning-Algorithms.git

# Navigate into the folder
cd Machine-Learning-Algorithms

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Linear\ Regression\ pro\ simple.ipynb
