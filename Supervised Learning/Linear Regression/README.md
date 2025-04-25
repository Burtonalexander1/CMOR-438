# Algorithm
Linear regression works by trying to predict a target value using a formula inspired by the $y=mx+b$ where $x$ may be a vector of multiple values. The algorithm seeks to decrease the average squared error between all predicted values and their corresponding observed values. Further details and implementation are in the code.


# Problem
Can we predict how many points an NBA player scored in a game based on how long they played, how many (and what type of) shots they attempted, and how many assists they earned? 

# Dataset
We will be using this [NBA 2023-2024 Box Scores Kaggle Dataset](https://www.kaggle.com/datasets/albi9702/nba-boxscore-season-2023-2024). The dataset contains all the Box Scores of NBA games during the 2023 - 2024 season. Specefically, we will be considering the following stats for each player and game,
- Minutes
- Field Goals Attempted (non three pointers)
- Three Points Attempted
- Free Throws Attempted
- Assists

In order to predict the total number of points a player scored in a given game.