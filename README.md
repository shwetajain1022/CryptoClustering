# CryptoClustering
##Overview
------------------
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques K-means clustering. The project explores the impact of dimensional reduction using Principal Component Analysis (PCA) on clustering.

##Steps
-------------
##Loading of Data and processing the data.
-----------
1. Scaling of the data using StandardScaler.
2. Finding the best value for k using the elbow method.
3. Clustering cryptocurrencies with K-means using the original scaled data.
4. Performing PCA to reduce the features to three principal components.
5. Finding the best value for k using the PCA data.

##Cluster cryptocurrencies with K-means using the PCA data.
--------------------------------------
1. Visualizing and comparing the results using hvPlot.
##Results
-------------------------
The project includes the following visualizations:

Elbow curve for the original data.
image.png

Elbow curve for the PCA data.
image.png

Scatter plot of cryptocurrency clusters based on the original data.
bokeh_plot (8)

Scatter plot of cryptocurrency clusters based on the PCA data.
bokeh_plot (9)

Conclusion
The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

Dependencies
Python
pandas
NumPy
scikit-learn
hvPlot
