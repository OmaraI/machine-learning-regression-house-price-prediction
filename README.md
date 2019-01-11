
This is a demonstration of a machine learning regression project. I predicted the value of home prices using the Ames, Iowa dataset. I used a variety of machine learning algorithms from scikit-learn and XGBoost. The XGBoost algorithm ended up creating the best model. 

See the accompanying Jupyter Notebook in this repo.

# Overview
In this project I'm documenting a machine learning workflow for a supervised learning regression task in Python. In particular, we are predicting house property prices with the popular Ames Housing Dataset.

We're going to try to minimize the RMSE. For the Kaggle competition associated with this exercise judges on the smallest Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Smaller error = better model. We're not overly concerned with optimizing every bit of performance, but more with demonstrating the machine learning process for this type of project.

We'll explore the data, do some data cleaning, and some feature selection. We'll explore a variety of supervised machine learning algorithms including linear regression variants, nearest neighbors, SVMs, and gradient boosted regression trees. We'll use pipelines and grid searches to look for preprocessing steps, models, hyperparameters that work well.
