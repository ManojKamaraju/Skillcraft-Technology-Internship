# Skillcraft Technology Internship – Machine Learning Projects

This repository contains machine learning projects completed during the Skillcraft Technology Internship. Each task focuses on a core ML concept applied to real-world data.

---

## 📌 Task 1: Linear Regression

**Objective:** Predict a continuous variable using one or more features.

**Model:**  
Simple Linear Regression:  
`y = β₀ + β₁x + ε`  
Multiple Linear Regression:  
`y = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ + ε`

**Use Case:** Predict house prices or similar metrics.

---

## 📌 Task 2: K-Means Clustering

**Objective:** Segment customers into groups based on features.

**Steps:**
- Initialize `K` clusters
- Assign data to nearest centroid
- Update centroids
- Repeat until stable

**Features Used:**
- Age
- Annual Income
- Spending Score

**Evaluation:** Silhouette Score

---

## 📌 Task 3: Cat vs Dog Classification (SVM + Feature Extraction)

**Objective:** Classify images as cat or dog using traditional ML.

**Steps:**
- Load images using PyTorch
- Apply MaxPooling and flattening
- Train Linear SVM on features
- Evaluate with classification report

---

## 📌 Task 4: Hand Gesture Recognition (CNN)

**Objective:** Classify hand gestures using a CNN model.

**Model:**
- Conv2D (32 filters, kernel size 3)
- MaxPooling
- ReLU
- LazyLinear (5 output classes)

**Training:**
- Loss: CrossEntropyLoss
- Optimizer: Adam (lr=0.001)
- Epochs: 10
- Batch size: 32

**Features:**
- 5 gesture classes
- Dataset loaded with `ImageFolder`
- GPU support with CUDA



## Acknowledgment

Developed under the Skillcraft Technology Internship to build practical machine learning skills.
