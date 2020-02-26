# Kmeans-InitializationAlgorithms-EuclideanVsManhattan
A comparison of Random. vs Far centroid initialization, with Euclidean vs Manhattan distance

## Dataset
- Each row is a document represented by a vector of features
- 4601 rows and 58 columns
- One dataset with Random initialized document centroids, and another with centroids initialized Far apart 

## Euclidean Distance Result
- On the 10 iteration of Kmeans, Random centroid initialization has 26.7% loss reduction
- On the 10 iteration of Kmeans, Far centroid initialization has 78.0% loss reduction

Thus, Far centroid initialization is better, which results in true clusters being split less often

## Manhattan Distance Result

- On the 10 iteration of Kmeans, Random centroid initialization has 17.7% loss reduction
- On the 10 iteration of Kmeans, Far centroid initialization has 49.98% loss reduction

Thus, Far centroid initialization is not better than Random initialization, because the latter relied on Euclidean distance.  With Far apart initialization, true clusters are split less often.
