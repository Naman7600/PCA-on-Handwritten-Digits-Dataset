# 🧠 PCA-Based Dimensionality Reduction on Handwritten Digits

## 📌 Project Overview

This project explores **Principal Component Analysis (PCA)** on the **Digits dataset** to reduce dimensionality while preserving maximum variance. It further evaluates how dimensionality reduction impacts **model performance (accuracy)**.

---

## 📊 Dataset Details

* **Source:** `sklearn.datasets.load_digits()`
* **Total Samples:** 1797
* **Image Size:** 8 × 8 pixels (grayscale)
* **Features:** 64 (flattened pixel values)
* **Classes:** 10 (digits 0–9)

---

## 🎯 Objectives

* Apply PCA for dimensionality reduction
* Retain maximum variance with fewer features
* Evaluate impact on **model accuracy**
* Compare performance before and after PCA

---

## 🔍 Methodology

### 🔹 1. Data Preprocessing

* Loaded dataset using sklearn
* Structured data using Pandas
* Verified dataset integrity

---

### 🔹 2. Feature Scaling

* Applied **StandardScaler**
* Ensured uniform contribution of features

---

### 🔹 3. PCA Implementation

* Applied PCA on scaled data
* Reduced dimensionality from **64 → optimal components**
* Selected components based on **cumulative explained variance (~90–95%)**

---

### 🔹 4. Model Training & Evaluation

* Split dataset into training and testing sets
* Trained machine learning model(s)
* Evaluated using **Accuracy Score**

---

## 📈 Results & Performance

### 🔸 Accuracy Comparison

| Model       | Accuracy |
| ----------- | -------- |
| With PCA    | 94.72%      |

> 📌 Observation:
> PCA reduced feature space significantly while maintaining comparable accuracy.

---

### 🔸 Key Findings

* PCA reduces computational cost ⚡
* Minimal loss in predictive performance
* Helps remove noise and redundant features

---

## 📊 Visualizations

* Scree Plot (Explained Variance)
* Cumulative Variance Plot
* Digit Image Visualization

---

## 🧠 Key Learnings

* PCA is effective for dimensionality reduction in image data
* Optimal components retain most variance
* Accuracy remains stable even after reduction

---

## ⚙️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
├── Pca Handson.ipynb
├── README.md
```

---

## 🚀 Future Enhancements

* Try multiple models (SVM, Random Forest, KNN)
* Hyperparameter tuning
* Use advanced techniques (t-SNE, UMAP)

---

## 📌 Conclusion

This project highlights how PCA can efficiently reduce dimensionality while maintaining strong model accuracy, making it a valuable preprocessing step in real-world ML pipelines.

---

## ⭐ If you found this useful

Feel free to ⭐ the repo and explore more ML projects!
