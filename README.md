Crypto Clustering: 
The Crypto Clustering focus on predicting if cryptocurrencies are affected by 24-hour or 7-day price changes by using python and unsupervised learning techniques, specifically K-means clustering.
Furthermore, it shows the impact of dimensionality reduction by using Principal Component Analysis (PCA) on clustering.

Steps: 
Load and preprocess the data.
Scale the data using StandardScaler.
Find the best value for k using the elbow method.
Cluster cryptocurrencies with K-means using the original scaled data.
Perform PCA to reduce the features to three principal components.
Find the best value for k using the PCA data.
Cluster cryptocurrencies with K-means using the PCA data.
Visualize and compare the results using hvPlot.

Conclusion:
The project analyzes the impact of using fewer features on clustering the data using K-means. Comparing the clustering results of the original data and the PCA data helps to understand the effect of dimensionality reduction on the clustering process.

Dependencies
Python
pandas
NumPy
scikit-learn
hvPlot
