# K-means Clustering & DBScan

## K-means
Hooray! Another $k$ based technique (so you know I'm going to like it :))! 

Similar to k-nearest neighbors, the k of k-means clustering is a user-chosen number, but most of the similarities end there. 

K-means clustering is a unsupervised learning technique, meaning the data we are analyzing is unlabeled. To sort through all of this data, k-means clustering tries to find clusters in the data. We choose 'k' distinct centroids to make k distinct, non-overlapping clusters. 

This technique works iteratively until centroids are "stable", and we have effectively pre-processed our data such that supervised learning can be performed on it!


## DBScan 

I think this name is pretty snazzy for a snazzy technique. DBScan is another clustering technique, but it uses the density of points to generate the different clusters. It identifies dense regions as clusters, and low density regions as noise. We will see more of how this work as we work through the notebook.

In this notebook, we will implement k-means clustering on the heart attack dataset once again to try and label who has/has not had a heart attack.
