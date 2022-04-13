#ML-clustering k-means

## Part1
#### implement the k-means algorithm using the Mahalanobis distance
Implement the k-means algorithm using the Mahalanobis distance instead of the standard Euclidean distance. Then, create a toy dataset with 2 or 3 dimensions (so it is possible to easily visualize the data) with roughly 500 data points. Such a dataset should be designed so that it allows you to show how and when k-means operating with the Mahalanobis distance works better than k-means equipped with the Euclidean distance and a centroid-based cluster representative.

#### Results:
![](./img/1.png)
![](./img/2.png)
![](./img/3.png)

#### Analysis
Based on the following experimental results, K-Means operating with Mahalanobis distance works undoubtedly better than K-Means equipped with Euclidean distance and a centroid-based cluster representative for linearly correlated elliptical data

## Part2
#### Implementaion of Vavies0Bouldin index for cluster validation
Implement the Davies-Bouldin index for cluster validation (intrinsic cluster validation). Then, perform model selection for finding the best partition order k of k-means. For this part of the project, use the standard k-means implementation operating with the Euclidean distance and centroids as cluster representatives. Perform simulations and comments on the results obtained on the dataset named "cluster_validation_data.txt" that has been provided with this notebook.

#### Results:
![](./img/4.png)

#### Analysis
The lower the davies bouldin value the better the cluster, and so from our graph we can conclude that data set: the best number of partitions of k were 3
