#  Speed-Dating-Match-Prediction-DM
 
In this assignment, we are going to predict the outcome of a specific speed dating session based on the profile of two people, so we can implement a recommendation system to better match people in speed dating events. We did have another online dating dataset (Tinder-like) but that one is super dirty which requires extensive cleaning, so we do this one instead. This is a binary classification task. Given a data sample (information about the dating session), we are going to predict the probability (0-1, float) that the dating session will lead to a successful match.

The dataset is clean, but has a lot of missing values. The strategy for missing value replacement has to be tuned. Also, as you can guess, this dataset is highly unbalanced (mostly unmatched). The idea of this assignment is to treat the complete workflow from data preprocessing to model training as a single pipeline, and search for the hyperparameters for this pipeline.


competition link: https://www.kaggle.com/competitions/cisc-873-dm-f22-a2
