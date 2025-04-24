# Algorithm
The Perceptron is a supervised learning algorithm used for binary classifications. At a high level, the algorithm works by finding a hyperplane to split the two categories in our data. In our case, since we only have two features, the algorithm will find a line to split our categories. The specifics of the algorithm and its implementation are shown in the code.


# Problem
In the NBA, there are five main positions. We will consider two of them for this project: the center (usually the largest) and the point guard (usually the smallest). Our objective is as follows: given a player's height and weight, can we identify which of the two positions the player is? The Perceptron will work well for our specific problem because there is a roughly linear trend between a player's height and weight.

# Dataset
We will be using the NBA Common Player Info from the following Kaggle [NBA Database](https://www.kaggle.com/datasets/wyattowalsh/basketball).  We will be focusing only on players who started playing in 2000 or later, and will be classifying their position specifically if they are a center or a guard. 
Our two features are
- Player Height
- Player Weight 