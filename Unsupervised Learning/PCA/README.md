# Algorithm
Principal Component Analysis (PCA) is a technique that transforms high-dimensional data into a lower-dimensional space while preserving as much variance as possible. It identifies principal components (orthogonal directions that capture the most variance in the data). The algorithm starts by computing the covariance matrix of the dataset, followed by an eigen decomposition to extract the principal components. Each principal component corresponds to an eigenvector, with its significance determined by the associated eigenvalue. The original data is then projected onto a lower-dimensional subspace spanned by the top principal components, allowing for simpler representation and visualization. An application is in the code.

# Problem
Can we determine outlier batters in baseball by considering a wide array of stats and simplifying them with PCA?

# Dataset
We will use the 2024 [PyBaseball Batting Stats](https://github.com/jldbc/pybaseball/tree/master) specifically
1. **OBP (On-Base Percentage)**
2. **SLG (Slugging Percentage)** 
3. **WAR (Wins Above Replacement)** 
4. **BB% (Walk Rate)**
5. **K% (Strikeout Rate)** 
6. **BABIP (Batting Average on Balls in Play)** 
7. **Barrel% (Barrel Rate)**

to determine 3 Principal Components and then determine outlier players.