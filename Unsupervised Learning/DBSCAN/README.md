# Algorithm
DBSCAN (Density-Based Spatial Clustering of Applications with Noise) works by identifying groups of densely packed points based on neighborhoods of points with radius ($\varepsilon$) and a minimum number of points ($k$) required to form a cluster. Instead of relying on a predefined number of clusters like K-means, DBSCAN classifies points as core, border, or noise based on their density. The algorithm then expands clusters from core points by including neighboring points within $\varepsilon$. Border points are connected to clusters but don't necessarily meet the density criteria, while noise points remain unclustered. DBSCAN continues this process until all dense regions are identified. Further specifics and the algorithm are in the code


# Problem
How can we cluster more complex collections of points?

# Dataset
We will create synthetic data with numpy to create two clusters of points: a spiral and a ball.