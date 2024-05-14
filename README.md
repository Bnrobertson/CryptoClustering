# Cryptocurrency Market Analysis with K-Means Clustering and PCA

This project aims to analyze cryptocurrency market data using K-Means clustering 
and Principal Component Analysis (PCA). The goal is to identify meaningful 
clusters of cryptocurrencies based on their market performance and visualize 
these clusters to gain insights.

# Introduction

In this project, I performed clustering on a dataset of cryptocurrencies to 
group them based on their market performance metrics such as price change percentages 
over different time periods. We then use PCA to reduce the dimensionality of the data 
and optimize our clustering results.

# Dataset

The dataset used in this analysis contains various performance metrics for multiple cryptocurrencies, including:

Price change percentage over 24 hours
Price change percentage over 7 days
Price change percentage over 14 days
Price change percentage over 30 days
Price change percentage over 60 days

The dataset is stored in **crypto_market_data.csv.**

The following libraries are required to run the code in this repository:

- pandas
- hvplot
- scikit-learn
- holoviews
- You can install the required libraries using pip:
pip install pandas hvplot scikit-learn holoviews

# Data Preparation

The data preparation steps include loading the dataset, normalizing the data using StandardScaler, 
and creating DataFrames for the scaled data.

# K-Means Clustering

We use the K-Means algorithm to cluster the cryptocurrencies based on the normalized data. 
The optimal number of clusters is determined using the Elbow method.

# Principal Component Analysis (PCA)

PCA is used to reduce the dimensionality of the data, making it easier to visualize and interpret the clusters.

# Visualization

We visualize the clusters using scatter plots. We compare the clusters formed with and without PCA.

# Results

The optimal number of clusters was determined to be 4 using the original data and 3 using the PCA-transformed data. 
The visualizations show distinct clusters, helping to understand the similarities and differences among cryptocurrencies 
based on their market performance.

# Conclusion

This project demonstrates the use of K-Means clustering and PCA in analyzing and visualizing cryptocurrency market data.
The results provide insights into the clustering of cryptocurrencies, which can be useful for market analysis and investment strategies.
