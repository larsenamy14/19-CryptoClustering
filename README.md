# Process
### Step 1: Prepare the data using StandardScaler()
### Step 2: Find the best value of k using the original scaled dataframe
### Step 3: Cluster cryptocurrencies with K-means using the original scaled dataframe
### Step 4: Optimize the cluster with Principal Component Analysis (PCA)
### Step 5: Find the best value of k using the PCA data
### Step 6: Cluster cryptocurrencies with K-means using the PCA data

# Conclusion
The impact of using fewer features to cluster the data using K-Means didn't have a huge impact on the elbow curve - both graphs have nearly identical slopes, although the graph that used the PCA modeled data had lower inertia values for each value of k. 
In the clustered scatter plot, the impact of using fewer features to cluster the data is that the different groups are further away from eachother and easier to distinguish as separate groups. PCA group 0, 1, and 2 are found in different areas of the graph while the original clusters 0, 1, and 2 are very close together and only cluster 3 is clearly separated from the mass of the data points. 
