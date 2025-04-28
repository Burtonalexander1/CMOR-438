
# Algorithm
K-nearest neighbors classifies data points by looking at their **nearest neighbors** in the feature space. Given an input, KNN finds some number **k** most similar points from the training set based on a chosen distance metric, usually Euclidean distance, and then votes on the majority -- that label is then assigned to our data point. Further specifics and the algorithm are in the code.

# Problem
In baseball, a pitch that is off target is considered a ball. Given a training set of pitches, can we categorize a pitch as a ball using KNN?

# Dataset
We will be the [PyBaseball API](https://github.com/jldbc/pybaseball/tree/master). Specifically, we will read Statcast data for the 2025 regular season. Statcast is a tool developed by the MLB to track various variables regarding pitches and hitting. We will be considering the following to predict if a pitch is a ball
* plate_x - the horizontal positioning of the pitch over the plate
* plate_z - the vertical positioning of the pitch over the plate