# Ensemble Methods

The main idea behind ensemble methods is combining the predictions of multiple models to produce a final prediciton. This leverages the concept that the crowd will predict more accurately than a single person (see jellybean guessing video lol). Below are some popular ensemble methods:

1) Bootstrapping. This resampling technique is random sampling with replacement from the training data. When one does this many times over, we get bagging. Bagging (bootstrap aggregating) involves training the same base learning algorithm on multiple subsets of the data. From that, we take the combined predictions (aggregation) and use it as a single prediction. This is barely better than random guessing, and honestly how I feel in my higher level math classes sometimes. The key idea is that it reduces the variance of a model by aggregating all of the individual subsets.


2) Random Forests. This ensemble method combines multiple decision trees, where each one is a subset of the training data and inputs. Similar to bagging, individual predictions are aggregated together to produce a final result. 


3) Boosting. Boosting is another techinque where multiple weak learners are combined into a strong learned. The final prediction is determined by aggregating the predictions of each of the weak learners. Examples of popular boosing algorithms include AdaBoost, Gradient Boosting Machines, and XGBoost. 