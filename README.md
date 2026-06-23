<div align="center">

# 🛍️ Customer Segmentation using Machine Learning

### Unsupervised Learning | K-Means Clustering | Hierarchical Clustering

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-green)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-KMeans-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

## 📌 Project Overview

This project applies unsupervised machine learning techniques to segment mall customers based on demographic and spending behavior attributes. Multiple clustering approaches were explored, compared, and validated to identify meaningful customer groups and derive actionable business insights.

---

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Identify customer segments using K-Means Clustering
- Determine optimal clusters using the Elbow Method
- Compare Income-Based and Age-Based Segmentation Models
- Validate clustering results using Hierarchical Clustering
- Analyze Gender vs Spending Behavior
- Apply Feature Engineering for Enhanced Segmentation
- Generate Business Insights

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
- SciPy
- Jupyter Notebook
- VS Code

---

## 📊 Dataset Information

### Dataset
**Mall Customers Dataset**

### Features

| Feature | Description |
|----------|------------|
| CustomerID | Unique Customer Identifier |
| Gender | Male / Female |
| Age | Customer Age |
| Annual Income (k$) | Annual Income |
| Spending Score (1-100) | Customer Spending Behavior Score |

---

## 🔍 Exploratory Data Analysis

### Analysis Performed

- Distribution Analysis
- Correlation Analysis
- Gender Analysis
- Missing Value Verification
- Outlier Detection
- 2D Visualizations
- 3D Visualization

### Key Findings

- Spending behavior varies significantly among customers.
- Annual Income and Spending Score provide strong segmentation potential.
- Customer groups are visually separable.
- Age influences spending patterns for specific customer groups.

---

## 🤖 Segmentation Model 1: Income & Spending Score

### Features Used

- Annual Income (k$)
- Spending Score (1-100)

### Methodology

1. Feature Scaling using StandardScaler
2. Elbow Method
3. K-Means Clustering
4. Cluster Visualization
5. Customer Persona Analysis

### Optimal Number of Clusters

**k = 5**

### Key Customer Segments

- High Income High Spending Customers
- High Income Low Spending Customers
- Standard Customers
- Budget Customers
- Young Enthusiastic Shoppers

### Business Insight

Income and spending behavior together provide highly meaningful customer segmentation for targeted marketing strategies.

---

## 👥 Segmentation Model 2: Age & Spending Score

### Features Used

- Age
- Spending Score (1-100)

### Methodology

1. Feature Scaling
2. Elbow Method
3. K-Means Clustering
4. Cluster Interpretation

### Optimal Number of Clusters

**k = 5**

### Key Insights

- Young High-Spenders
- Young Moderate-Spenders
- Older Moderate-Spenders
- Older Low-Spenders
- Senior Customer Group

### Business Insight

Age-based segmentation reveals behavioral differences that may not be visible in income-based clustering.

---

## 🌳 Hierarchical Clustering

Hierarchical Clustering was applied to validate the K-Means results.

### Findings

- Dendrogram confirmed a 5-cluster structure.
- Results closely matched K-Means segmentation.
- Cluster separation was clearly visible.

---

## 🚻 Gender vs Spending Score Analysis

### Findings

- Male and Female customers exhibit similar spending distributions.
- No substantial difference was observed between spending scores.
- Gender alone is not a strong predictor of customer spending behavior.

---

## ⚙️ Feature Engineering

### Engineered Feature

```python
Spending_Efficiency = Spending Score / Annual Income
```

### Purpose

This feature measures how efficiently customers spend relative to their income levels.

### Results

- Improved customer differentiation.
- Produced well-separated customer groups.
- Revealed behavioral patterns beyond traditional income-spending analysis.

---

## 📈 Business Insights

✅ High-income, high-spending customers represent premium target customers.

✅ Budget-conscious customers are highly price-sensitive and suitable for discount campaigns.

✅ Young customers exhibit stronger spending tendencies.

✅ Feature engineering improved cluster interpretability.

✅ Multiple clustering approaches produced consistent segmentation results.

---

## 📁 Project Structure

```text
customer-segmentation-kmeans/

├── customer_segmentation.ipynb
├── Mall_Customers.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Future Enhancements

- DBSCAN Clustering
- Gaussian Mixture Models (GMM)
- Customer Lifetime Value Analysis
- Interactive Dashboard using Streamlit
- Real-Time Customer Segmentation

---

## 📌 Conclusion

This project successfully demonstrated how unsupervised machine learning techniques can be used to discover hidden customer segments and behavioral patterns. By combining K-Means Clustering, Hierarchical Clustering, Gender Analysis, and Feature Engineering, meaningful customer groups were identified that can support targeted marketing strategies and data-driven business decisions.

---

# 👨‍💻 Author

## Bhavya Sree Gubba

🎓 B.Tech CSE (AI & ML) 🏫 VIT-AP University

<br>

## 📬 Connect With Me

[![Email](https://img.shields.io/badge/EMAIL-CONTACT%20ME-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gubbabhavya@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-BHAVYA%20SREE-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bhavya-sree-22122006bs/)

[![GitHub](https://img.shields.io/badge/GITHUB-BHAVYASREE--22-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bhavyasree-22)

<br>

⭐ If you found this project useful, consider giving the repository a star.
