Customer Segmentation Analysis Using K-Means Clustering

 Project Overview

This project explores customer segmentation using the iFood customer dataset to identify distinct customer groups based on income, age, product spending and purchasing behaviour.

The goal is to understand how customers differ in their spending patterns and shopping preferences, enabling businesses to develop targeted marketing strategies, improve customer engagement and make data-driven business decisions.

Using K-Means Clustering, the analysis groups customers with similar characteristics into segments and use the visualisation techniques to explore the differences between these groups.

Objectives
The Dataset used was downloaded from kaggle

Dataset: iFood Customer Dataset (`ifood_df.csv`)

Records show: 2,205 customers
•39 columns
•No missing values detected during initial inspection.

Key variables used for clustering include:

- `Income`: Customer income.
- `Age`: Customer age.
- `MntWines`: Amount spent on wine products.
- `MntMeatProducts`: Amount spent on meat products.
- `NumWebPurchases`: Number of online purchases.
- `NumStorePurchases`: Number of in-store purchases.
- `NumCatalogPurchases`: Number of catalogue purchases.
- `NumWebVisitsMonth`: Number of website visits per month.

Tools 

- Python
- Google Colab
- Pandas: Data loading and manipulation.
- Matplotlib and Seaborn: Data visualisation.
- Scikit-learn: Data preprocessing, K-Means clustering and PCA.

 Methodology
1. Imported the dataset and examined its structure, data types, descriptive statistics and missing values.

2. Selected eight demographic, spending and purchasing behaviour variables for customer segmentation.

3. Applied StandardScaler to standardise the selected features before clustering.

4. Used the Elbow Method to examine clustering inertia across different values of K, from 1 to 10.

5. Applied the K-Means algorithm with four specified clusters to group customers according to similarities in their characteristics.

6. Compared average income, age, product spending and purchasing behaviour across customer segments.

7. Applied Principal Component Analysis (PCA) to reduce the selected features to two dimensions for visualising customer segments.

 Key Findings

The displayed cluster summaries shows differences in customer income and purchasing behaviour:

- Cluster 0: Recorded the highest average income (approximately 77,477) and the highest average spending on wine and meat products among the displayed groups.
- Cluster 1: Had the lowest average income (approximately 34,475), with comparatively low spending across the analysed product categories.
- Cluster 2: Recorded an average income of approximately 60,560, with relatively high wine spending and more frequent online purchases than the other displayed groups.

The visualisations explore customer distribution across segments and the relationship between income and wine spending.

 Business Value
Customer segmentation helps businesses move beyond a one-size-fits-all marketing approach.

The analysis provides basis for:

- Developing targeted marketing campaigns.
- Identifying high-value customer groups.
- Improving customer retention strategies.
- Personalising product recommendations and promotions.
- Understanding customer purchasing preferences across sales channels.

 Skills Demonstrated

Data Cleaning, Exploratory Data Analysis, Feature Selection, Data Standardisation, Unsupervised Machine Learning, K-Means Clustering, Principal Component Analysis (PCA), Data Visualisation and Business Insight Generation.
