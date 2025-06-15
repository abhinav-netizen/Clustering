# Clustering
Clustering on customers

Program: Python

Source: Superstore sales data
Encoding: latin1

Main fields used:
Customer ID,
Sales,
Quantity,
Order count

Objective: To identify meaningful customer segments based on purchasing behavior using K-Means clustering, enabling strategic marketing and customer relationship management.

Key Steps

Data Aggregation
  Grouped by Customer ID, aggregating total sales, quantity, and number of orders.

Outlier Detection
  Applied IQR method to detect outliers in both Sales and Quantity.

Outlier Treatment
  Removed outliers to form a non_outliers dataset for clustering.
  Retained outliers for separate visualization and analysis.

Feature Transformation
  Applied signed log transformation to normalize skewed distributions.

Data Scaling
  Standardized features using StandardScaler.

Clustering
  Applied K-Means clustering (k = 2 to 12).

Evaluated clusters using:
  Inertia (Elbow Method)

Silhouette Score
Visualization
Created violin plots to explore distribution of features by cluster.
Analyzed both regular clusters and outlier-driven segments.

Mapped customer segments to strategic labels like:
  Retain,
  Improve,
  Upsell,
  Cultivate,
  Maximize, etc.



Cluster Analysis
Each cluster was analyzed for:
  Mean Sales, Quantity, OrderCount
  Strategic customer insights and segment names

Visual comparison using:
  Bar charts,
  Line plots,
  Violin plots,

