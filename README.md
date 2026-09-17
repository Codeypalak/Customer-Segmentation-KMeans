# Customer Segmentation using K-Means Clustering

## Project Overview

This project focuses on segmenting customers based on their demographic and purchasing behavior using K-Means clustering.

## Objective

To identify meaningful customer groups based on:

- Age
- Income
- Total Spending
- Total Purchases

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing

- Handled missing Income values using median imputation.
- Removed unrealistic age values.
- Removed an extreme income outlier.
- Created `Age`, `Total_Spending`, and `Total_Purchases` features.
- Standardized clustering features using StandardScaler.

## Methodology

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Feature Scaling
6. K-Means Clustering
7. Cluster Profiling
8. Data Visualization

## Customer Segments

### Cluster 0 — Older High-Value Customers
Higher-income customers with high spending and purchasing activity.

### Cluster 1 — Low-Value / Budget Customers
Lower-income customers with relatively low spending and purchasing activity.

### Cluster 2 — Young High-Value Customers
Higher-income customers with high spending and purchasing activity.

### Cluster 3 — Older Low-Engagement Customers
Older customers with moderate income and relatively low spending.

## Results

The K-Means model divided the customers into four distinct segments based on age, income, spending, and purchasing behavior.

## Conclusion

Customer segmentation can help businesses understand different customer groups and support targeted marketing and customer engagement strategies.
