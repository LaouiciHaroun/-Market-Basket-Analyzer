# 🛒 Market Basket Analyzer

A Streamlit-powered interactive application for analyzing customer purchasing behavior using the Apriori algorithm. It visualizes frequent itemsets, optimizes store layout based on item association, and helps identify purchasing patterns.

---

## 📊 Dataset Description

- **Format**: `.csv` or `.xlsx`
- **Structure**:
  - `transaction_ID`: Unique identifier for each transaction.
  - Product columns (e.g., `A`, `B`, `C`, ...) with **binary values**:
    - `1`: Product was purchased
    - `0`: Product not purchased

---

## 💻 Development Environment

- **Language**: Python 3.10+
- **Framework**: Streamlit
- **Libraries**:  
  `pandas`, `mlxtend`, `plotly`, `numpy`

---

## 🧠 Features

- 📈 Frequent Itemset Mining using **Apriori**
- 🔢 Adjustable **minimum support**
- 🗺️ **Store Layout Map**: Visualizes product positions using `(x, y)` coordinates
- 🧭 Optimized layout: Reorganizes products by co-occurrence proximity to the store entrance `(0, 0)`
- 📉 Visual charts for support levels

---

This project is licensed under the MIT License. Feel free to use, modify, and share it with attribution



