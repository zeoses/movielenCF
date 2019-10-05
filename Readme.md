# Movielen Collaborative Filtering

This is a recommande base system create with [Python](https://www.python.org/) and use [MovieLens](https://grouplens.org/datasets/movielens/) Database .

for write , We used [colab](https://colab.research.google.com) .

Step 1 : we read data and create UserItem Matrix .

Step 2 : we Splite data For Train and Test (80/20) .

Step 3 : used [K-Means](https://en.wikipedia.org/wiki/K-means_clustering) Algorithm for Clustering train Data

Step 4 : This is a long and very important step. The description of this step is really long, so read this [article](https://www.sciencedirect.com/science/article/pii/S0957417417302713) to see all the work done. But in summary we calculated Pearson's similarity and then predicted using each similarity for each item and average score. And finally, to find out how useful this method is, we calculated the three values of [Accuracy](https://en.wikipedia.org/wiki/Accuracy_and_precision), [Precision](https://en.wikipedia.org/wiki/Accuracy_and_precision), [Recall](https://en.wikipedia.org/wiki/Precision_and_recall)

Step 5 : Show All Result.
