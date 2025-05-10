
# 📊 Crypto Clustering

This project uses machine learning and data visualization to **cluster cryptocurrencies** based on various market attributes. The goal is to group cryptocurrencies with similar behaviors or characteristics to aid in investment insights or market analysis.

---

## 🧠 Key Concepts

- **K-Means Clustering**
- **Data Preprocessing**
- **Principal Component Analysis (PCA)**
- **Visualization of Clusters in 2D and 3D**
- **Financial Feature Engineering**

---

## 📁 Files

- `Crypto_Clustering.ipynb` — Main notebook with code for data preparation, clustering, and visualization.
- `crypto_market_data.csv` *(assumed)* — Historical or current data on cryptocurrencies.
- `README.md` — This file.

---

## 📌 Features

- Loads and cleans a dataset of cryptocurrency market data.
- Normalizes and scales data for machine learning.
- Applies **K-Means clustering** with different numbers of clusters.
- Uses **PCA** to reduce dimensionality for easier visualization.
- Generates **2D and 3D scatter plots** showing cluster groupings.
- Compares the effect of using fewer vs. more features on clustering results.

---

## 📷 Visual Output

The notebook provides:
- Side-by-side cluster plots before and after PCA.
- 3D scatter plot showing cluster separation.
- Analysis of clustering quality and interpretability.

---

## ⚙️ Requirements

Make sure to install the required Python libraries:

```bash
pip install pandas sklearn matplotlib seaborn plotly
```

---

## 🚀 How to Run

1. Open the notebook using JupyterLab or Jupyter Notebook.
2. Run each cell in order.
3. Modify cluster count (`k`) to experiment with different grouping levels.

---

## 📝 Insights

> Using fewer features (after PCA) made the clusters more visually interpretable but may have reduced the model’s ability to capture deeper patterns in the data. There is a trade-off between simplicity and richness of insight.
