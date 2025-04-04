# 🧠 PCA IMPLEMENTATION

This project demonstrates **Principal Component Analysis (PCA)** applied on the **MNIST dataset** to reduce dimensionality while preserving key features of handwritten digit images.

---

## 📁 Dataset

The dataset used is the **MNIST handwritten digits dataset**, downloaded from [Kaggle](https://www.kaggle.com/). It contains:

- 60,000 training images
- 10,000 test images
- Each image is 28x28 pixels (784 features)

---

## 🔧 Tools & Libraries

- Python 🐍
- NumPy & Pandas
- Matplotlib & Seaborn (for visualization)
- Scikit-Learn (for PCA and data preprocessing)

---

## 📊 Project Steps

1. **Data Loading & Preprocessing**
   - Read the MNIST dataset
   - Normalize pixel values
   - Optional: Visualize a few digit samples

2. **PCA Application**
   - Apply PCA to reduce from 784 dimensions to N components
   - Plot explained variance ratio vs. number of components
   - Reconstruct digits from reduced dimensions

3. **Visualization**
   - Compare original and reconstructed images
   - 2D scatter plots of digits after PCA for clustering insight

---

## 📈 Results

- PCA reduced dimensions while retaining ~95% variance with ~150 components
- Reconstructed images were visually close to originals
- 2D PCA plots showed visible clustering of different digits

---

## 💡 Insights

- PCA is effective for compression and visualization of high-dimensional data like MNIST.
- You can balance between compression (fewer components) and reconstruction quality.

