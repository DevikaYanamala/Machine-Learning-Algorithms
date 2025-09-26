# 🌼 K-Means Clustering on Iris Dataset

This project applies **K-Means clustering** to the **Iris dataset**, a well-known dataset in machine learning.  
The dataset consists of 150 samples of iris flowers with 4 features:  
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

The goal is to cluster the flowers into 3 groups and compare the clusters with the true species labels:  
- Setosa  
- Versicolor  
- Virginica  

---

## 📊 Project Workflow
1. Load the Iris dataset from scikit-learn  
2. Convert into a pandas DataFrame for easy exploration  
3. Apply **KMeans clustering** with `n_clusters=3`  
4. Add cluster labels to the DataFrame  
5. Compare cluster assignments with actual species  
6. Visualize clustering results using scatter plots  

---

## ⚙️ Features
- Unsupervised learning with K-Means  
- Data exploration with pandas  
- Cluster labeling and comparison with ground truth  
- Visualization of clusters using matplotlib  

---

## 🚀 Tech Stack
- **Python 3**  
- **pandas** → Data handling  
- **NumPy** → Numerical operations  
- **scikit-learn** → KMeans algorithm, Iris dataset  
- **matplotlib** → Data visualization  


---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/DevikaYanamala/kmeans-iris.git
   cd kmeans-iris
   pip install -r requirements.txt
   jupyter notebook KMeans_exercise.ipynb
