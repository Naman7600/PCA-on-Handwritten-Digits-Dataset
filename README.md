# PCA-on-Handwritten-Digits-Dataset

## 📌 Project Overview

This project demonstrates **Principal Component Analysis (PCA)** on the classic **Digits dataset** from `sklearn`. The goal is to understand how high-dimensional image data (64 features) can be reduced while preserving most of the important information.

---

## 📊 Dataset Description

* Dataset: `load_digits()` from sklearn
* Total samples: **1797**
* Each sample: **8×8 grayscale image**
* Features: **64 pixel values**
* Target: Digits from **0 to 9**

---

## 🔍 Project Workflow

### 1. Data Loading & Exploration

* Loaded dataset using `load_digits()`
* Converted into Pandas DataFrame
* Checked:

  * Missing values ✅
  * Duplicate values ✅

---

### 2. Data Understanding

* Each row represents a flattened image (64 features)
* Visualized sample image using `matplotlib`
* Verified corresponding label

---

### 3. Feature Scaling

* Applied **StandardScaler**
* Important because PCA is variance-based

---

### 4. PCA (Dimensionality Reduction)

* Applied PCA on scaled data
* Transformed 64-dimensional data → lower dimensions
* Analyzed:

  * Explained variance
  * Cumulative variance

---

### 5. Visualization

* Scree Plot:

  * Individual explained variance
  * Cumulative explained variance
* Helped identify optimal number of components

---

## 📈 Key Insights

* First few principal components capture **major variance**
* Significant dimensionality reduction possible with minimal information loss
* PCA helps:

  * Reduce noise
  * Improve efficiency
  * Simplify models

---

## 🧪 Sample Visualization

* Digit image plotted using:

  * `plt.imshow()`
* Helps understand how raw pixel data looks

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🚀 Future Improvements

* Apply classification models (Logistic Regression, SVM, etc.)
* Compare performance before vs after PCA
* Hyperparameter tuning
* Use advanced techniques like t-SNE or UMAP

---

## 📌 Conclusion

This project shows how PCA can effectively reduce dimensionality in image data while retaining important patterns, making it useful for machine learning tasks.

---
