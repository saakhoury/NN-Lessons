K-means is an unsupervices machine learning technique that allows us to cluster data points. This enables us to find 
patterns in the data that can help us analyze it more effectively. K-means is an iterative algorithm, which means that 
it will converge to the optimal clustering over time. 

To run a k-means clustering: 
    - Specify the number of clusters (k)
    - Randomly initialize the centroid for each cluster
    - Determine which data poits belong to which cluster by find the closest centroid to each data point
    - Update the centroids based on the geometric mean of all the data points in the cluster
    - Run last two steps iteratively until the centroids stop changing 

