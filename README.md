# Project Title: K-Means Clustering for Customer Segmentation 

This project implements K-Means clustering to segment customers based on their annual income and spending score. It utilizes the Mall_Customers.csv dataset and performs the following steps:

1. Data Loading and Exploration:

- Imports necessary libraries (pandas, NumPy, matplotlib, seaborn, scikit-learn)
- Loads the customer data from the CSV file into a pandas DataFrame.
- Displays the first few rows and checks for missing values

2. Feature Selection:

- Selects the "Annual Income (k$)" and "Spending Score (1-100)" columns for clustering

3. Determining the Optimal Number of Clusters:

- Implements the elbow method to identify the suitable number of clusters using the Within-Cluster Sum of Squares (WCSS) metric
- Visualizes the WCSS values for different cluster numbers using a line plot

4. K-Means Clustering:

- Creates a K-Means model with the chosen number of clusters (replace with the value you determined)
- Fits the model to the selected features
- Predicts cluster labels for each data point and stores them in the Y variable

5. Visualization:

- Creates a scatter plot to visualize the customer clusters based on annual income and spending score
- Colors data points according to their assigned clusters
- Plots the centroids (cluster centers) for each cluster
