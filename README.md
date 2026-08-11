# 🛒 Wholesale Customer Segmentation

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![K-Means](https://img.shields.io/badge/K--Means-Clustering-green)

An unsupervised Machine Learning project that segments wholesale customers based on their annual spending behavior across different product categories.

## 📌 Project Overview

This project focuses on segmenting wholesale customers based on their annual spending behavior across different product categories using **K-Means Clustering**.

The goal is to identify groups of customers with similar purchasing patterns and understand their spending behavior.

## 📊 Dataset

The dataset contains annual spending information for six product categories:

- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

## 🔍 Exploratory Data Analysis

I performed exploratory data analysis to understand:

- Dataset structure and statistical summary
- Feature distributions
- Relationships between spending categories
- Correlations between features
- Potential outliers

## ⚙️ Data Preprocessing

The numerical features were standardized using **StandardScaler** before applying K-Means because the features have different spending ranges.

## 🤖 K-Means Clustering

I used **K-Means Clustering**, an unsupervised machine learning algorithm, to group customers based on their spending behavior.

### Choosing the Number of Clusters

I evaluated different values of K using:

- Elbow Method
- Silhouette Score

Based on these evaluations, an appropriate number of clusters was selected for customer segmentation.

## 📈 Cluster Visualization

The resulting clusters were visualized using scatter plots.

For example:

- Grocery Spending
- Detergents & Paper Spending

These visualizations help show how customers are distributed across different spending patterns.

## 🎯 Customer Segmentation

After clustering, I analyzed the average spending of each cluster across all six product categories.

The clusters were then mapped to more understandable business categories:

- **Low Annual Spending**
- **Medium Annual Spending**
- **High Annual Spending**

## 📊 Cluster Analysis

Cluster centers were converted back to the original spending scale to make the results easier to interpret.

This allowed each customer segment to be compared based on its spending behavior across the six product categories.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📁 Project Structure

```text
WholesaleCustomer/
│
├── k means.ipynb
├── Wholesale customer.csv
└── README.md
