# K-Means Clustering Machine Learning Algorithm

## 📌 Overview
This repository contains an implementation of the **K-Means Clustering Algorithm** in Python.  
The experiment is done in Google Colab and includes dataset loading, clustering, visualization, and final results.

---

## 📘 Theory

### ⭐ What is Clustering?
Clustering is an **unsupervised machine learning technique** used to group similar data points together based on patterns or similarity.

### ⭐ What is K-Means Algorithm?
K-Means is one of the most widely used clustering algorithms.  
It divides the data into **K clusters** by minimizing the distance between points and the cluster center (centroid).

### 📌 Steps in K-Means:
1. Choose the number of clusters **K**  
2. Randomly initialize K centroids  
3. Assign each data point to the nearest centroid  
4. Recalculate centroid positions  
5. Repeat until convergence  

### 📌 Key Concepts:
- **Centroid:** Center of the cluster  
- **Inertia:** Sum of squared distances (used to measure performance)  
- **Elbow Method:** Used to find optimal K  

---

## 🛠️ Tools & Libraries Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn (`sklearn.cluster.KMeans`)
---

## ▶️ How to Run
1. Open the notebook in Google Colab.  
2. Upload the dataset.  
3. Run all cells.  
4. Visualization will show cluster groups.
