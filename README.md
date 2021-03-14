Problem statement:
From the given ‘Iris’ dataset, predict the optimum number of clusters and
represent it visually.

About the algorithm:
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster.

k-means algorithm:
1. Choose the number of clusters k
2. Select k random points from the data as centroids
3. Assign all the points to the closest cluster centroid
4. Recompute the centroids of newly formed cluster
5. Repeat steps 3 and 4
