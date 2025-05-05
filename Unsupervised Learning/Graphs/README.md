# Algorithm
Label Propagation is a machine learning algorithm that spreads labels through a graph based on node connections. Starting with labeled points, the algorithm iteratively updates unlabeled nodes by propagating label information across edges. This continues until convergence, adjusting labels based on neighboring influences. The implementation and other graph algorithms are in the code.

# Problem
Can we determine the College Football Conferences using only the 2024 College Football Schedule (ie, determining clusters of teams that play each other)? We will also consider the largest subset of teams, none of which played each other(independence number), and the largest number of teams that all played each other (largest clique size).

# Dataset
We will use the [ 2024 Sports Reference College Football Schedule](https://www.sports-reference.com/cfb/years/2024-schedule.html). We will consider all matchups of teams that played 3 or more games to ensure that only FBS schools are considered. We will also only be considering the regular season.