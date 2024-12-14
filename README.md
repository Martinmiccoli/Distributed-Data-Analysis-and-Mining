# 💳 Credit Card Fraud Analysis and Customer Segmentation

Welcome to the **Distributed Data Analysis and Mining** project! This repository showcases our work in analyzing synthetic credit card transaction data to uncover fraud and gain actionable insights into customer behavior.

---

## 🚀 Project Overview

This project explores a **synthetic dataset** of over **1.29 million transactions**, created with the [Sparkov Data Generator](https://github.com/namebrandon/Sparkov_Data_Generation). It combines **exploratory analysis**, **clustering**, and **machine learning models** to tackle key challenges like **fraud detection** and **customer segmentation**. 

### Key Highlights:
- **Cutting-edge machine learning**: From K-Means clustering to XGBoost classification.
- **Scalable technology**: All processing and analysis done with **PySpark**.
- **Real-world challenges**: Addressing class imbalance, geospatial patterns, and feature engineering.

---

## 🗂️ Project Structure

### 1️⃣ Exploratory Data Analysis (EDA)
- Explored **data distributions**, correlations, and missing values.
- Enhanced features by adding:
  - **Geospatial insights**: Distances from home.
  - **External data**: Income levels and holiday indicators.
- Visualized fraudulent transactions to uncover patterns.

### 2️⃣ Clustering
- **Customer Segmentation**:
  - Identified 6 customer clusters based on demographic and spending habits.
  - Example: High-spending, highly-educated men vs. low-educated frequent shoppers.
- **Transaction Clustering**:
  - Segmented transactions by amount, frequency, and geospatial dimensions.
  - Used **Isolation Forest** for anomaly detection.
- **Geospatial Analysis**:
  - Mapped fraud patterns using **Folium**.
  - Discovered that fraudulent transactions often occur at medium distances from home.

### 3️⃣ Behavioral Analysis
- **Spending Habits**:
  - Analyzed clusters by age, gender, and education.
  - Example: Younger users prioritize entertainment, while older ones focus on groceries.
- **Time-Based Trends**:
  - Peak spending for "Personal Care" at 7 PM.
- **Geospatial Behavior**:
  - Clustered users by spending proximity and volume.

### 4️⃣ Classification: Fraud Detection
- Tackled class imbalance with **SMOTE** and **ADASYN**.
- Built and evaluated models including:
  - Logistic Regression, Random Forest, and XGBoost.
  - Best result: **ROC-AUC of 0.999** and F1-Score of 0.89.
- Enhanced explainability with **LIME**, revealing top predictors like transaction category and amount.

---

## 🔍 Insights

- Fraudulent transactions are tied to **specific distances** and **transaction types**.
- **Cluster-based segmentation** helps refine fraud detection and customer profiling.
- These findings offer a dual advantage: 
  - **Improved fraud prevention systems**.
  - **Tailored business strategies** to enhance customer engagement.

---

## 📦 Technologies Used

- **Frameworks**: PySpark, XGBoost, LIME
- **Visualization**: Matplotlib, Folium, Radar Charts
- **Data Engineering**: SMOTE, PCA, Isolation Forest

---

## 📊 Results at a Glance

| Metric              | Best Model (XGBoost) |
|---------------------|----------------------|
| **Precision**       | 0.929                |
| **Recall**          | 0.775                |
| **F1-Score**        | 0.845                |
| **ROC-AUC**         | 0.999                |

---

## 🤝 Contributors

A collaborative effort by **Group 2** from the MSc Data Science and Business Informatics program at the University of Pisa:

- **Pietro Argento**
- **Martin Miccoli**
- **Aldo Montinaro**
- **Marco Poiani**

---

## 📖 Learn More

- [📑 Full Project Report](./[DDAM_Group2_2425.pdf](https://github.com/Martinmiccoli/Distributed-Data-Analysis-and-Mining/blob/main/Group2_DDAM_2425%5BReport%5D.pdf))
- [Sparkov Data Generator](https://github.com/namebrandon/Sparkov_Data_Generation)
- [US State Boundaries Dataset](https://public.opendatasoft.com/explore/dataset/us-state-boundaries/export/)
- [Income Data](https://fred.stlouisfed.org/release/tables?eid=259515&rid=249)

---

Let’s analyze data smarter, not harder! 🚀
