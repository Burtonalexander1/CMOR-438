
# Algorithm
**Ensemble Methods** are combinations of multiple machine learning algorithms used to increase accuracy. A common example is **random forests**. If decision trees are like playing 20 questions, then random forests are like gathering a whole panel of experts to play and vote on best answer. Random forests incorporate the following ensemble techniques: 
* **Bootstrapping**: training each tree on a different part of the data,
* **Random Feature Selection**: training trees on different sets of features
* **Voting**:  selecting the most popular answer

By combining the results of multiple trees, the random forest model achieves better generalization and robustness, while reducing the risk of overfitting. To see more details and other ensemble techniques, see the code.



# Problem
We will revisit pitch classification (described in the Decision Tree readme), but with more features and ensemble techniques.

# Dataset
We will be the [PyBaseball API](https://github.com/jldbc/pybaseball/tree/master). Specifically, we will read Statcast data for the 2025 regular season. Statcast is a tool developed by the MLB to track various variables regarding pitches and hitting. We will be considering the following to predict if a pitch type
* release_speed -  pitch velocity
* release_spin_rate - pitch spin rate
* pfx_x - horizontal movement in feet from the catcher's perspective
* pfx_z - vertical movement in feet from the catcher's perspective
* plate_x - horizontal position of the ball when it crosses home plate from the catcher's perspective.
* plate_z - vertical position of the ball when it crosses home plate from the catcher's perspective.
* release_pos_x - -   horizontal release position of the ball measured in feet from the catcher's perspective.
* release_pos_z - vertical release position of the ball measured in feet from the catcher's perspective.
* release_extension - release extension of pitch in feet as tracked by Statcast.
