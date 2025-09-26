# 🧮 Logistic Regression - Multiclass Classification

This project applies **Logistic Regression** to the **Digits dataset** (handwritten digits 0–9) using **scikit-learn**.  
The model predicts the correct digit from pixel values of 8×8 images.

---

## 📊 Project Workflow
1. **Load Data**  
   - Used `sklearn.datasets.load_digits()` to fetch the dataset.  

2. **Exploration**  
   - Checked dataset attributes (`data`, `target`, `images`).  
   - Displayed example digit images using Matplotlib.  

3. **Preprocessing**  
   - Converted data into suitable features and labels.  

4. **Model Training**  
   - Built a **Logistic Regression** classifier (`sklearn.linear_model.LogisticRegression`).  
   - Trained on training data.  

5. **Evaluation**  
   - Calculated model accuracy on test data.  
   - Verified predictions against actual labels.  

---

## 🚀 How to Run  

```bash
# Clone repository
git clone https://github.com/<DevikaYanamala>/Machine-Learning-Algorithms.git
cd Machine-Learning-Algorithms

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook "Logistic Multiclass.ipynb"
