# Cuda-Kmeans

## Done As A part of Heterogenous Parallel Computing Course

###In k-means, a data point is comprised of several values, called features. By dividing a cluster of data objects into k sub-clusters, k -means represents all the data objects by the mean values or centroids of their respective sub-clusters.Since the complexity and time taken by the sequential compiler is high it is proposed to use the GPU for parallelization to the maximum extent possible.

## Objective

The traditional sequential KMeans Algorithm is of com-
plexity O(nk) where n is the number of points and k is the
number of clusters. In the new algorithm prroposed the
complexity will be O(nk/p) where p is the degree of paral-
lelism. The bjective of the project is to implement parallel
version of k means image segmentation algo- rithm using
CUDA parallel programming language.
