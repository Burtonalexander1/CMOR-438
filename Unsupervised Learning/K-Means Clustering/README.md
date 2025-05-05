# Algorithm
K-means clustering works by grouping input data into a pre-determined number ($k$) of clusters using a Euclidean distance, which measures how close a data point is to the cluster's centroid. The algorithm then recalculates the centroids and regroups the data into clusters with the new centroids. This process is repeated until it converges. Further specifics and the algorithm are in the code

# Problem
We will be considering different ways to measure how effective a value of $k$ is for our clusters. We will then try to determine the best value of $k$ from this measure.

# Dataset
We will be using the sklearn make_blobs function to experiment with different numbers of clusters and variabilities of clusters.