# Process
### Step 1: 
Prepare the data using StandardScaler()
### Step 2: 
Find the best value of k using the original scaled dataframe
### Step 3: 
Cluster cryptocurrencies with K-means using the original scaled dataframe
### Step 4: 
Optimize the cluster with Principal Component Analysis (PCA)
### Step 5: 
Find the best value of k using the PCA data
### Step 6: 
Cluster cryptocurrencies with K-means using the PCA data

![image](https://github.com/user-attachments/assets/9b98e259-f3c6-493a-bae9-0f43f6ac02fd)

# Conclusion
The impact of using fewer features to cluster the data using K-Means didn't have a huge impact on the elbow curve - both graphs have nearly identical slopes, although the graph that used the PCA modeled data had lower inertia values for each value of k. 
In the clustered scatter plot, the impact of using fewer features to cluster the data is that the different groups are further away from eachother and easier to distinguish as separate groups. PCA group 0, 1, and 2 are found in different areas of the graph while the original clusters 0, 1, and 2 are very close together and only cluster 3 is clearly separated from the mass of the data points. 

# Challenges
The hover_cols parameter did not initially work on the scatter plots. I used 2 lines of code in my terminal to install bokeh.

jupyter labextension install @bokeh/jupyter_bokeh

conda install -c conda-forge jupyterlab
