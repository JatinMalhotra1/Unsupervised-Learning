# Water Treatment Plant Clustering
After analysing the dataset it was found that records of four stages of water treatment have been kept, they being

1. Entry to plant
2. Moving to primary settler
3. Moving to secondary settler
4. Moving out of the treatment plant
The dataframe was divided into above four sub datasets, for cluster formations. 
Different dataframes have been made as, according to our opinion, each dataframe acts as target of previous.
While calculating the Silhouette score, we found scores to be in range of 0.1 to 0.3, and hence no clear clusters were formed based on K-means method .
Moving forward we also did agglomerative clustering for all the dataframes, and based the clusters on pH level of water,of clusters and hence we have some clarity with that
