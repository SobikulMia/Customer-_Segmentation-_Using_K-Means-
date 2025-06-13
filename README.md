# 🛍️ Customer Segmentation Using KMeans Clustering

## 📌 Project Overview
This project uses **KMeans Clustering** to segment mall customers based on their **Annual Income** and **Spending Score**. It helps businesses understand different customer groups to improve marketing strategies and services.

---

## 🧠 Machine Learning Techniques Used
- **KMeans Clustering**
- **Elbow Method** with **KneeLocator** to find optimal clusters
- **Label Encoding** for categorical data
- **Data Visualization** with Seaborn & Matplotlib
- **Model Saving** with `joblib`

---

## 📂 Dataset Features
- `CustomerID` – Unique customer ID (removed for clustering)
- `Gender` – Converted to numeric using LabelEncoder
- `Age` – Customer age
- `Annual Income (k$)` – Renamed to `Income`
- `Spending Score (1–100)` – Renamed to `Score`

---

## 🛠️ Key Steps in the Project
1. Load and clean the dataset
2. Encode categorical columns
3. Select features (`Income` & `Score`) for clustering
4. Use Elbow Method to find the best number of clusters
5. Train KMeans model and assign cluster labels
6. Visualize clusters, centroids, and new customer prediction
7. Save the trained model with `joblib`

---

## 📊 Cluster Visualization

> Predict cluster for a new customer (example):
```python
New Customer (Income: 15, Score: 39) falls in Cluster 1

👨‍💻 Author
Made with ❤️ by a passionate ML learner
