# Mall Customer Segmentation

A machine learning project utilizing K-Means Clustering to group customers based on demographics (age, gender) and spending patterns to optimize targeted marketing strategies.Features include data visualization, the Elbow Method for optimal cluster selection, and 3D scatter plots

## Project Objective
The goal of this project is to divide a mall's customer base into distinct groups (segments) based on shared characteristics. This allows businesses to create personalized marketing campaigns and improve customer retention.

## Dataset
- **Source:** [Kaggle Mall Customers Dataset](https://www.kaggle.com/shwetabh123/mall-customers)
- **Features:** CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100).

## Methodology
1. **Exploratory Data Analysis (EDA):** Visualizing distributions of age and income.
2. **Data Preprocessing:** Standardizing features to ensure the clustering is not biased by scale.
3. **Clustering:** Implementing **K-Means Clustering**.
4. **Optimization:** Using the **Elbow Method** to find the ideal number of clusters.

## Business Insights
By the end of the analysis, we identify groups such as:
* **High Income, High Spending:** The "Target" group.
* **High Income, Low Spending:** The "Careful" group.
* **Low Income, High Spending:** The "Careless" group.
