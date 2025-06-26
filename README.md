# Customer Segmentation Analysis

This project performs a **customer segmentation analysis** for an e-commerce company using machine learning techniques. By analyzing customer behavior and purchase patterns, we group customers into meaningful segments that help improve marketing and business strategies.

# Objective

To cluster customers into distinct groups based on their demographics and purchase behavior, enabling targeted marketing and personalized strategies.

# Dataset

The dataset contains customer details such as:
- Income
- Spending on various product categories
- Number of web/store/catalog purchases
- Recency of last purchase
- Household information (kids/teens)

 **File Used:** `ifood_df.csv`

# Tools & Libraries

- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn (KMeans, StandardScaler, PCA)**

# Steps Performed

1. **Data Loading & Exploration**
2. **Data Cleaning**
3. **Descriptive Statistics**
4. **Feature Selection**
5. **Data Scaling**
6. **K-Means Clustering**
7. **PCA for Dimensionality Reduction**
8. **Cluster Visualization**
9. **Insights & Recommendations**

# Results

Customers were segmented into 4 meaningful clusters:
- **High-Value Loyal**: High spenders, less frequent visits
- **Budget Online Shoppers**: Prefer web purchases, moderate spend
- **Family Mid-Spenders**: Balanced spending across categories
- **Low Engagement**: Low spend and engagement

# Output

- Labeled segments added to the dataset
- Cluster visualizations using PCA
- Exported file: `segmented_customers.csv`

# Insights

> This segmentation helps the business:
- Tailor marketing strategies
- Design personalized offers
- Improve customer retention
- 
# Future Work

- Deploy segmentation model with a dashboard (e.g., Power BI or Streamlit)
- Automate customer insights updates over time


