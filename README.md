# CryptoClustering

module 19 challenge

# Project Overview

The goal of this challenge was to use unsupervised learning using methods such as k-means clustering to predict if cryptocurrencies are affected by 24 hour or 7-day price changes.
The steps taken to complete this challenge are as follows:

1.) Prepare the data by creating a scaled dataframe.

2.) Find the optimal value for k by creating an elbow plot.

3.) Cluster the cryptocurrencies using k-means.

4.) Optimize the clusters using pca to reduce the features.

5.) Find the best value for k using the new pca data.

6.) Cluster the cryptocurrencies with k-means using the pca data.

7.) Visually compare the plots.


# Technologies

- Python
- Jupyter Notebook
- sklearn
- hvplot
- pandas

# Plots

1.) cryptocurrency data

![image](https://github.com/Natphipps/CryptoClustering/assets/130694752/d9378b3c-4361-4528-9d87-df0f0fa099fe)

2.) elbow curve for original scaled data

![image](https://github.com/Natphipps/CryptoClustering/assets/130694752/75abecee-9586-46c2-bc76-c74f005cc10c)

3.) cryptocurrency clustering of original data using 4 features

![image](https://github.com/Natphipps/CryptoClustering/assets/130694752/009dd0fa-bfd3-4699-8593-01f52588fde0)

4.) elbow curve for new pca data

![image](https://github.com/Natphipps/CryptoClustering/assets/130694752/c44b5695-9f04-4e19-b09d-36a207f57e12)

5.) cryptocurrency clustering of pca data using 3 features

![image](https://github.com/Natphipps/CryptoClustering/assets/130694752/3e9abd49-7de9-46ba-a9a5-9a867bf22e0b)







