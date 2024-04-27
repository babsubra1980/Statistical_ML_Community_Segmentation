# Statistical_ML_Community_Segmentation

UT Final Project - Spring 2024

The objective of this project is to perform RFM analysis and apply unsupervised learning techniques, specifically k-Means++ clustering, to distinguish different groups within a community. The project aims to identify meaningful clusters based on socio-economic indicators without prior labels in the dataset. By leveraging dimensionality reduction and advanced visualization methods, the goal is to provide insights into community structures and characteristics.

# Project Goal

In this project, will use transnational data set from an online retail store which contains all the transactions occurring between certain dates. Will segement the customers based on RFM (R (Recency): Number of days since last purchase, F (Frequency): Number of tracsactions and M (Monetary): Total amount of transactions (revenue contributed)) so that the company can target its customers efficiently. Apply the K-means algorithm to the normalized RFM data. Will analyze the clusters obtained from K-means to understand the characteristics of each segment and then develop targeted marketing strategies or campaigns tailored to the needs and behaviors of each customer segment identified.

image.png

Our goal is to cluster the customers in the given dataset to:

Identifiy valuable customers

Increase revenue and customer retention

Understand customer trends and behaviors

RFM (Recency, Frequency, Monetary) analysis is a marketing technique used to segment customers based on their transaction history. It involves analyzing three key metrics:

Recency: How recently a customer made a purchase.
Frequency: How often a customer makes a purchase.
Monetary: How much money a customer spends.

K-means clustering is a popular unsupervised machine learning algorithm used for clustering data points into groups based on similarity. It works by iteratively assigning data points to clusters and updating the cluster centroids until convergence.

Combining RFM analysis with K-means clustering can help businesses identify different customer segments based on their purchasing behavior.

Here's how you can apply K-means clustering to RFM data:

RFM Calculation: Calculate the RFM values for each customer based on their transaction history.

Normalization: Normalize the RFM values to ensure that all three metrics are on the same scale.

K-means Clustering: Apply the K-means algorithm to the normalized RFM data. Choose the number of clusters (K) based on business objectives or using techniques like the elbow method or silhouette score.

Interpretation: Analyze the clusters obtained from K-means to understand the characteristics of each segment. Assign meaningful labels to each cluster based on their RFM values.

Actionable Insights: Develop targeted marketing strategies or campaigns tailored to the needs and behaviors of each customer segment identified.

By combining RFM analysis with K-means clustering, businesses can gain valuable insights into their customer base and tailor their marketing efforts to maximize customer satisfaction and revenue.
