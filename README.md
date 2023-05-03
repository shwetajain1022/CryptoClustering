# CryptoClustering
Overview
------------------
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques K-means clustering. The project explores the impact of dimensional reduction using Principal Component Analysis (PCA) on clustering.

Steps
-------------
Loading of Data and processing the data.
-----------
1. Scaling of the data using StandardScaler.
2. Finding the best value for k using the elbow method.
3. Clustering cryptocurrencies with K-means using the original scaled data.
4. Performing PCA to reduce the features to three principal components.
5. Finding the best value for k using the PCA data.

Cluster cryptocurrencies with K-means using the PCA data.
--------------------------------------
1. Visualizing and comparing the results using hvPlot.
Results
-------------------------
The project includes the following visualizations:

Elbow curve for the original data.
--------------------------------------
![image](https://user-images.githubusercontent.com/40103518/235860425-fd94d05d-da67-42b6-b703-ccdacd73ffb5.png)


Elbow curve for the PCA data.
---------------------------------
![image](https://user-images.githubusercontent.com/40103518/235860282-bd09f6bd-9f53-4e38-87bc-0a321bc3ca96.png)

Scatter plot of cryptocurrency clusters based on the original data.
-------------------------------------
![image](https://user-images.githubusercontent.com/40103518/235860687-750b8893-177e-4192-a0da-64b064c1f779.png)

Scatter plot of cryptocurrency clusters based on the PCA data.
------------------------------------------------------
![image](https://user-images.githubusercontent.com/40103518/235860796-b57ea808-8b17-4950-b480-8b03a8307101.png)

Conclusion
-------------------------------------
#### Answer the following question: 

  * **Question:** After visually analysing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** With PCA having fewer dimensions, help in understanding the clustering of data visually and easily.It helps has ML algorithm run faster as it doesnot need to train the model on as much data.
