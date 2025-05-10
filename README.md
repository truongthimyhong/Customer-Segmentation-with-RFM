# Customer-Segmentation-with-RFM
# 🧠 Customer Segmentation using RFM & K-Means

A data analysis project applying the RFM model and K-Means clustering to segment customers and evaluate differences between groups using statistical hypothesis testing.

## 📘 Project Overview

This project was developed as part of the *Data Analysis with Python* course at the University of Economics - University of Danang.  
The focus is on segmenting customers based on transaction behavior and validating the segmentation using statistical tests.

## 🎯 Objectives

- Apply RFM (Recency, Frequency, Monetary) model to evaluate customer value.
- Use K-Means clustering to group customers with similar behaviors.
- Perform ANOVA and Tukey HSD tests to assess the statistical significance of differences between clusters.
- Provide practical insights for targeted marketing and customer relationship management (CRM).

## 📂 Dataset

- Source: Superstore sales data (public dataset)
- Records: 1000 transactions
- Attributes: Customer info, order details, location, sales amount
- Time span: 2021–2024

## 🛠 Technologies & Tools

- **Python**
  - `pandas` for data manipulation
  - `matplotlib` & `seaborn` for visualization
  - `scikit-learn` for clustering and preprocessing
  - `scipy.stats` for statistical testing
- **Jupyter Notebook**
- Data normalization via **Z-score**
- Outlier removal using **IQR method**

## 🔍 Methodology

1. Data cleaning and preprocessing  
2. RFM metric calculation  
3. Normalization of RFM using Z-score  
4. Outlier removal (IQR)  
5. Determining optimal cluster count (Elbow method)  
6. Customer clustering with K-Means  
7. Hypothesis testing using ANOVA & Tukey HSD

## 📊 Results Summary

- The optimal number of clusters was **4**.
- Significant differences were found among clusters in terms of Recency, Frequency, and Monetary value.
- Visualizations helped interpret the behavioral profiles of each customer group.
- The findings support CRM strategies like targeted promotions, retention plans, and personalized communication.

## 📌 Conclusion

Customer segmentation using RFM and K-Means provides a powerful foundation for data-driven marketing.  
Statistical testing adds confidence to the insights, ensuring the clusters represent real differences in customer behavior.

---

*Developed for academic purposes. All data used is anonymized and publicly available.*
