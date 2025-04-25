# Algorithm
Logistic regression works by estimating the probability that an input belongs to a specific class using a formula inspired by the *sigmoid function*, which turns a weighted sum of features into a value between 0 and 1 (a probability). The algorithm then seeks to minimize a measure called the binary cross-entropy, representing how accurate our predictions are. This measure is useful here because it gives an extra penalty when the model is confident in an incorrect prediction -- rather than the perceptron, which penalizes all incorrect predictions the same. Further specifics and the algorithm are in the code.

# Problem
Given the average performance of an NBA player over the course of a season, can we predict if they are a center?

# Dataset
We will be using this [NBA 2023-2024 Box Scores Kaggle Dataset](https://www.kaggle.com/datasets/albi9702/nba-boxscore-season-2023-2024). The dataset contains all the Box Scores of NBA games during the 2023 - 2024 season. Specifically, we will be considering the following stats per player and game
- Three Point Attempts
- Rebounds
- Blocks
- Field Goal Percentage

and averaging them out by player over the course of a season in order to predict if a given player is a center.