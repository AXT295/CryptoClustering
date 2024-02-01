# CryptoClustering

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Prepare the Data
-Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
-Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

Find the Best Value for k Using the Original Scaled DataFrame
What is the best value for k?
Answer: 4

Cluster Cryptocurrencies with K-means Using the Original Scaled Data

Optimize Clusters with Principal Component Analysis
What is the total explained variance of the three principal components?
Answer: 89%

Find the Best Value for k Using the PCA Data
What is the best value for k when using the PCA data?
Answer: 3
Does it differ from the best k value found using the original data?
Answer: For the original data, 4, was better.

Cluster Cryptocurrencies with K-means Using the PCA Data
What is the impact of using fewer features to cluster the data using K-Means?
Using fewer features in K-Means clustering can lead to a loss of information, oversimplification of the data, and potentially less accurate cluster assignments. The choice of features is crucial, as it can affect the quality of clusters, computational efficiency, sensitivity to noise, and introduce biases in cluster assignments. Careful consideration is needed to balance computational efficiency with the need to retain important information for meaningful clustering results.

Visualize and Compare the Results
Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means?
The inertia has been changed by reducing the features. Therefore, compared to the scale data, PCA results were better for clusters. We've seen more precise clustering with the use of the optimal PCA value of 2.


References
The Ohio State University Data Analytics Bootcamp

