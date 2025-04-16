# Customer Segmentation with K-Means Clustering 🎉

Welcome to my Customer Segmentation project! 📊 This is a Machine Learning project where I used K-Means Clustering to group customers from the Mall Customers dataset based on their income and spending habits.

## Overview
- **Objective**: Segment customers into distinct groups for targeted marketing.
- **Tools Used**: Python, Pandas, Scikit-learn, Matplotlib.
- **Model**: K-Means Clustering with 4 clusters.
- **Visualization**: Scatter plot showing customer segments and centroids.

## Dataset
- **Source**: Mall Customers Dataset from Kaggle (https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).
- **Details**: Contains columns like CustomerID, Age, Annual Income (k$), and Spending Score (1-100).

## Methodology
- Loaded and preprocessed the dataset.
- Applied StandardScaler to normalize features.
- Used K-Means to create 4 clusters and visualized them with a scatter plot.
- Analyzed cluster centers to derive insights.

## Results
- Successfully identified 4 customer groups:
  - High-income, high-spending shoppers.
  - Low-income, high-spending (possible credit users).
  - Average-income, average-spending customers.
  - Low-income, low-spending budget-conscious individuals.
- Visualized with a scatter plot.

## What I Learned
- **Unsupervised Learning**: Understood how K-Means works to find natural groupings.
- **Data Preprocessing**: Mastered feature scaling with StandardScaler.
- **Visualization**: Learned to create and interpret scatter plots for insights.
- **Analysis**: Gained skills in deriving actionable business insights from clusters.

## How to Run
1. **Install Dependencies**:
   ```bash
   pip install pandas scikit-learn matplotlib
