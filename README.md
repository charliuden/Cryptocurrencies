# Cryptocurrencies

February 6th, 2021

## Purpose of Analysis

This analysis looks at cryptocurrencies currently traded on the market. A cluster analysis was used to identify ways in which cryptocurrencies can be grouped to create a classification system for new investments. 

- *Deliverable 1:* Preprocessing the Data for PCA

This involves bucketing and hot coding categorical columns as well as standardizing the data.

- *Deliverable 2:* Reducing Data Dimensions Using PCA

The data was reduced to three principal components. 

- *Deliverable 3:* Clustering Cryptocurrencies Using K-means

An elbow curve indicates a K-means analysis with k=4 or four clusters.

- *Deliverable 4:* Visualizing Cryptocurrencies Results

The results of the scatter plot can be visualized in a table and  3D and 2D scatter plots. 

## Analysis Results:
The results of a k-means analysis can be seen in the elbow curve below. The elbow curve transitions to a more horizontal direction at about k=4 clusters. This indicates that 4 clusters should be used in the unsupervised machine learning algorithm. 

![elbow_curve.png](https://github.com/charliuden/Cryptocurrencies/blob/main/readme_images/elbow_curve.png)

A 3D scatter plot provides a visual of the three principal componenets and four clusters. 

![3D_scatter_clusters.png](https://github.com/charliuden/Cryptocurrencies/blob/main/readme_images/3D_scatter_clusters.png)
