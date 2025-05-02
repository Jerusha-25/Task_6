# 🌸 K-Nearest Neighbors (KNN) Classification – Iris Dataset

## 🔍 Objective
This project implements the **K-Nearest Neighbors (KNN)** algorithm to perform classification using the classic **Iris dataset**. The process includes data normalization, model training, evaluation, and decision boundary visualization.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas** – for data handling  
- **Scikit-learn** – for machine learning modeling and evaluation  
- **Matplotlib** – for plotting and visualization  
- **NumPy** – for numerical operations  

---

## 📊 Dataset: Iris
The **Iris dataset** contains measurements of 150 iris flowers from three species:
- Setosa  
- Versicolor  
- Virginica  

Each sample has the following features:
- SepalLengthCm  
- SepalWidthCm  
- PetalLengthCm  
- PetalWidthCm  

The goal is to classify the **species** based on these features.

---

## 🧪 Steps Followed

### 1. Load and Explore the Dataset
- Loaded the Iris dataset using `sklearn.datasets.load_iris`.
- Extracted feature matrix (`X`) and target labels (`y`).

### 2. Normalize Features
- Applied **StandardScaler** to normalize all numeric feature values for better distance calculation in KNN.

### 3. Train-Test Split
- Split data into **training (80%)** and **test (20%)** sets using `train_test_split`.

### 4. KNN Classification
- Used `KNeighborsClassifier` from `sklearn.neighbors`.
- Experimented with different values of **K** (e.g., 1, 3, 5, 7).

### 5. Model Evaluation
- Evaluated predictions using:
  - **Accuracy Score**
  - **Confusion Matrix**

### 6. Decision Boundary Visualization
- Selected two features: **PetalLengthCm** and **PetalWidthCm**.
- Plotted decision boundaries using `matplotlib` and meshgrid to visually represent model performance for different K values.

---

## 📈 Results
- The model showed high accuracy, especially for `K=3` and `K=5`.
- Decision boundaries clearly distinguish **Setosa**, while **Versicolor** and **Virginica** show some overlap.
- Accuracy and confusion matrix vary slightly with different K values.

---



