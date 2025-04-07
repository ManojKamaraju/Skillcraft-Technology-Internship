# Skillcraft-Technology-Internship
# 📌 K-Means Clustering – Customer Segmentation Analysis

## 🔍 Overview

This project implements **K-Means Clustering** to segment customers based on key features, as part of **Task 2** of the **Skill Craft Technology Internship**. Unsupervised machine learning is used to identify distinct groups of customers, helping businesses target each segment more effectively.

---

## 📚 What is K-Means Clustering?

**K-Means** is an unsupervised clustering algorithm that partitions a dataset into *K distinct non-overlapping clusters*. Each data point belongs to the cluster with the nearest mean, serving as a prototype of the cluster.

### ⚙️ Algorithm Steps:

1. Initialize `K` cluster centroids.
2. Assign each point to the nearest centroid.
3. Recompute centroids based on cluster members.
4. Repeat steps 2–3 until convergence.

---

## 🧠 Objective

To group customers based on selected features (e.g., income, age, etc.) using K-Means, and evaluate the quality of clusters using the **Silhouette Score**.

---

## 📁 Dataset

The dataset used (`data.csv`) contains customer attributes such as:

- `Age`
- `Annual Income`
- `Spending Score (1-100)`

> The target column (`Spending Score`) is dropped before clustering to maintain the unsupervised learning approach.

---

## 🧪 Evaluation Metric

- **Silhouette Score**: Measures how well each data point fits within its cluster. A value near **+1** indicates good clustering.

---

## 🧾 Project Steps

1. **Load and inspect the dataset** using `pandas`.
2. **Preprocess data** by removing the target variable.
3. **Train KMeans** using scikit-learn with `n_clusters=2`.
4. **Evaluate cluster quality** using the silhouette score.
5. Optionally visualize clusters using `matplotlib` and `seaborn`.

