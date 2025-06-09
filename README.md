# 🛍️ Customer Segmentation Analysis for Retail Business

A Data Science Project using K-Means Clustering, PCA, and EDA to uncover actionable customer segments for targeted marketing strategies.

---

## 📌 Problem Statement

A retail business wants to improve its marketing efforts by better understanding customer behavior. The goal is to:
- Segment customers based on demographics and spending behavior.
- Personalize marketing campaigns (e.g., discounts, loyalty programs).
- Optimize resource allocation by targeting the right audience.

---

## ❓ Business Questions

- How many distinct customer segments exist?
- What defines each segment? (e.g., “Young Budget Shoppers” vs. “Affluent Big Spenders”)
- How can the business tailor promotions for each group?

---

## 🎯 Project Objective

To apply unsupervised machine learning and dimensionality reduction techniques for meaningful customer segmentation using:

- ✅ K-Means Clustering
- ✅ Principal Component Analysis (PCA)
- ✅ Exploratory Data Analysis (EDA)

---

## 🔧 Steps Involved

### 1️⃣ Data Preprocessing
- Handle missing data.
- Convert income from `k$` to actual dollars.
- Rename columns for clarity (`Spending_Score`).
- One-hot encoding for categorical variables (e.g., `Gender`).
- Standardize numerical features.

### 2️⃣ Exploratory Data Analysis (EDA)
- Univariate analysis: Histograms of Age, Income, and Spending Score.
- Bivariate analysis: Pair plots and trend identification.
- Correlation matrix: Detect multicollinearity.

### 3️⃣ Dimensionality Reduction (PCA)
- Scale features and apply PCA.
- Analyze explained variance (e.g., PC1 explains 37%).
- Visualize reduced components for natural groupings.

### 4️⃣ Clustering (K-Means)
- Use Elbow Method to find optimal `k`.
- Validate with Silhouette Score.
- Apply K-Means and assign clusters to customers.

### 5️⃣ Visualization & Interpretation
- PCA Scatter plot with cluster colors.
- Segment profiles (mean Age, Income, Spending Score).
- Heatmaps for comparison.
- Business labels for each segment (e.g., “Cluster 3: High-Income Luxury Spenders”).

---

## 📊 Expected Outcome

- ✅ 5–6 well-defined customer segments.
- ✅ Cluster characteristics and marketing labels.
- ✅ Actionable insights for targeted promotions.
- ✅ Visualizations understandable by non-technical stakeholders.

---

## 📁 Files Included

- `Mall_Customers.csv` — Original dataset
- `Mall_Customers_Transformed.csv` — Cleaned and preprocessed data
- `README.md` — Project overview

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 💡 Business Impact

This segmentation model helps:
- Deliver personalized marketing.
- Improve customer retention.
- Focus resources on high-value customers.

---

