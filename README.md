# Customer-Segmentation-Analysis

## Project Overview
This project aims to perform customer segmentation on a dataset of mall customers using k-means clustering. By analyzing various features such as age, gender, annual income, and spending score, we can identify distinct groups of customers with similar characteristics. These insights can help businesses develop targeted marketing strategies to better serve each customer segment.

## Dataset
The dataset used in this project is `Mall_Customers.csv`, which includes the following columns:
- `CustomerID`: Unique ID assigned to each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Spending score assigned by the mall, ranging from 1 to 100



## Data Exploration
First, we load and explore the dataset to understand its structure and identify any missing values. Summary statistics and data distributions are visualized to gain insights into the data.

## Data Preprocessing
We preprocess the data by encoding categorical variables and scaling numerical features to prepare them for clustering.

## Determining the Number of Clusters
We use the Elbow Method to determine the optimal number of clusters for k-means clustering.

## K-Means Clustering
Based on the Elbow Method, we choose 4 as the optimal number of clusters and perform k-means clustering on the dataset.

## Cluster Analysis
We analyze the characteristics of each cluster to gain insights into customer behavior.

## Results Visualization
We visualize the clusters in a 3D space to understand the distribution and characteristics of each segment.

## Conclusion
The customer segmentation results reveal four distinct groups:

- Cluster 0: Mainly older males with a lower spending score despite a decent income.
- Cluster 1: Younger females with a higher spending score and slightly lower income.
- Cluster 2: Primarily older females with a moderate spending score.
- Cluster 3: Younger males with higher income and substantial spending.

==> These clusters provide valuable insights for targeted marketing strategies. Cluster 0 and Cluster 2, consisting of older individuals, may benefit from value-driven offerings, considering their lower spending propensity. On the other hand, Cluster 1 and Cluster 3, representing younger demographics, present opportunities for marketing higher-spending products.
