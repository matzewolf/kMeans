# kMeans
k-means (unsupervised learning/clustering algorithm) implemented in MATLAB. 

Cluster_2D_Visualization.m is a script that generates random (uniformly) distributed data points, 
runs both kMeans.m and MATLAB's built-in kmeans function, measures and compares their performance (i.e. computing time)
and visualizes the final clusters and the distribution of the data points in the clusters in a histogram.

kMeans.m implements k-means (unsupervised learning/clustering algorithm). Technical Details:
- The initial centroids are randomly selected out of the set of all data points (every data points maximum once).
- The stopping condition is that no changes to any cluster is made.

MATLAB's kmeans function uses slightly different default methods: See https://www.mathworks.com/help/stats/kmeans.html

clustering_app.mlapp opens an App with GUI where you can randomly generate data points and cluster them. You can re-hit all buttons to see the randomness in both point generation and the clustering algorithm.

clustering_app.mlappinstall installs the MATLAB App in the MATLAB Editor.
