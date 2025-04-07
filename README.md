# Skillcraft-Technology-Internship
# 🐾 Cat vs Dog Classification using Feature Extraction and SVM

## 🔍 Overview

This project implements an image classification model to distinguish between cats and dogs. The model uses basic feature extraction techniques (MaxPooling and Flatten) followed by a **Support Vector Machine (SVM)** classifier. This is a classical approach that combines deep learning-based feature representation with traditional machine learning classifiers.

---

## 🧠 Objective

To classify images of cats and dogs using extracted features and train a linear SVM classifier on those features for accurate prediction.

---

## 🧾 Methodology

1. **Dataset Loading**: Images are loaded using `ImageFolder` from PyTorch, assuming each class (cat/dog) is in its respective subdirectory.

2. **Feature Extraction**:
   - Input images are transformed into tensors.
   - A custom `FeatureExtractor` applies MaxPooling to reduce dimensionality.
   - Flattened outputs serve as feature vectors for classification.

3. **Model Training**:
   - Features and labels are extracted from the entire dataset.
   - The dataset is split into training and testing sets.
   - A linear SVM classifier is trained using `scikit-learn`.

4. **Evaluation**:
   - Predictions are made on the test set.
   - `classification_report` is used to measure precision, recall, and F1-score.

