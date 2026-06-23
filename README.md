# 🛍️ Customer Segmentation using Machine Learning

## 📌 Overview

This project applies unsupervised machine learning techniques to segment mall customers based on demographic and spending behavior attributes. Multiple clustering approaches were explored, compared, and validated to identify meaningful customer groups and derive actionable business insights.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Identify customer segments using K-Means Clustering
- Determine optimal clusters using the Elbow Method
- Compare Income-Based and Age-Based segmentation
- Validate results using Hierarchical Clustering
- Analyze Gender vs Spending behavior
- Apply Feature Engineering for enhanced segmentation

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

---

## 📊 Dataset

**Mall Customers Dataset**

| Feature | Description |
|----------|------------|
| Gender | Male / Female |
| Age | Customer Age |
| Annual Income (k$) | Annual Income |
| Spending Score (1-100) | Spending Behavior Score |

---

## 🔍 Exploratory Data Analysis

Performed:

- Distribution Analysis
- Correlation Analysis
- Gender Analysis
- 2D Visualizations
- 3D Visualization

### Key Findings

- Spending behavior varies significantly among customers.
- Annual Income and Spending Score provide strong segmentation potential.
- Customer groups are visually separable.

---

## 🤖 Segmentation Models

### Model 1: Income & Spending Score

**Features Used**
- Annual Income (k$)
- Spending Score (1-100)

**Optimal Clusters:** 5

**Key Segments**
- High Income High Spending
- High Income Low Spending
- Average Customers
- Budget Customers
- Young Enthusiastic Shoppers

---

### Model 2: Age & Spending Score

**Features Used**
- Age
- Spending Score (1-100)

**Optimal Clusters:** 5

**Key Insights**
- Young High-Spenders
- Young Moderate-Spenders
- Older Moderate-Spenders
- Older Low-Spenders
- Senior Customer Group

---

## 🌳 Hierarchical Clustering

Hierarchical Clustering was applied to validate K-Means results.

### Findings

- Dendrogram confirmed a 5-cluster structure.
- Results closely matched K-Means segmentation.
- Cluster separation was clearly visible.

---

## 🚻 Gender vs Spending Analysis

### Findings

- Male and Female customers show similar spending patterns.
- No major spending differences were observed.
- Gender alone is not a strong predictor of spending behavior.

---

## ⚙️ Feature Engineering

### Engineered Feature

```python
Spending Efficiency = Spending Score / Annual Income