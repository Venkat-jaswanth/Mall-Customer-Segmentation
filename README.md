# Mall-Customer-Segmentation
Welcome to the Mall Customer Segmentation project! This repository contains an insightful data science project where we analyze customer data using K-Means clustering, a powerful unsupervised machine learning algorithm. By leveraging this technique, we identify distinct segments of mall customers to help businesses tailor their marketing strategies effectively.

Project Overview
In this project, we explore the mallcustomers.csv dataset, which includes various features about customers such as:

CustomerID: Unique identifier for each customer.
Gender: Gender of the customer.
Age: Age of the customer.
Annual Income (k$): Annual income of the customer in thousand dollars.
Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature.
Our goal is to perform customer segmentation to uncover meaningful patterns and insights that can be used for targeted marketing.

Key Features
Data Preprocessing: Cleaning and scaling the data to ensure it is suitable for clustering.
Exploratory Data Analysis (EDA): Visualizing data distributions and relationships between features.
K-Means Clustering: Applying the K-Means algorithm with different values of n_clusters and n_init to determine the optimal number of clusters.
Silhouette Analysis: Using silhouette scores to evaluate the quality of the clusters.
Cluster Visualization: Plotting clusters to visualize customer segments in a 2D space.
Technical Highlights
Data Preprocessing:

Handling missing values, if any.
Standardizing features to have zero mean and unit variance for optimal clustering performance.
Exploratory Data Analysis (EDA):

Utilizing histograms, box plots, and scatter plots to understand feature distributions and relationships.
Gender distribution analysis and income versus spending score insights.
K-Means Clustering:

Implementing the K-Means algorithm from scikit-learn with a range of cluster numbers (k) from 1 to 7.
Iterating over multiple initializations (n_init values: 10, 25, 50) to ensure convergence to a global optimum.
Evaluation with Silhouette Score:

Calculating silhouette scores for each clustering configuration to measure the quality of clusters.
Selecting the optimal n_clusters based on the highest silhouette score.
Cluster Visualization:

Using PCA (Principal Component Analysis) for dimensionality reduction.
Visualizing clusters in a 2D plot to interpret and analyze customer segments.

Results
Through our analysis, we have identified distinct customer segments that exhibit unique spending behaviors and income levels. These insights can help mall management and marketers design targeted campaigns to enhance customer satisfaction and boost sales.
