# hierarchical-clustering-industry-indices
Implementation of hierarchical clustering on market-cap weighted industry index data obtained from Ken French’s website (http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html). 

In this report I have impemented an hierarchical clustering algorithm with a Spearman correlation-based
distance to measure dissimilarity between observations, and complete linkage to estimate
dissimilarities between clusters. I have found an optimal number of 6 clusters and concluded that the 
clustering analysis is robust after employing a stability test based on bootstrapping and Jaccard similiarity score.

A potential practical application of this clustering algorithm would be to construct diversified
portfolios, consisting of the best performing indices for each cluster. 

**This repo contains:**
- A pdf report explaining in detail the methodology and results
- Jupyter notebook for the analysis
