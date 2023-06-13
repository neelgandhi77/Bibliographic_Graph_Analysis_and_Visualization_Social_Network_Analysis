# Bibliographic_Graph_Analysis_and_Visualization_Social_Network_Analysis

This repository contains code for analyzing and visualizing a bibliographic graph using a heterogeneous network. The methodology involves data preparation, graph construction, node feature extraction, text processing and vectorization, dimensionality reduction, clustering, cluster visualization, and variable distribution evaluation.

## Methodology
### Data Preparation: 

Clean the dataset by removing missing values and duplicates, select relevant columns, and save the cleaned dataset.

### Graph Construction: 

Build a directed graph using NetworkX, where nodes represent paper titles and citations, and edges represent connections between them.

### Node Feature Extraction: 

Extract node features, such as the number of topics or papers associated with each node.

### Text Processing and Vectorization: 

Process and vectorize textual data using techniques like TF-IDF to convert text into numerical representations.

### Dimensionality Reduction: 

Apply Truncated SVD to reduce the dimensionality of the vectorized data while preserving essential information.

### Clustering: 

Use K-means clustering to group similar data points based on their reduced dimensional representations.

### Cluster Visualization: 

Visualize the clusters using scatter plots to gain insights into the clustering results and patterns in the data.

### Variable Distribution Evaluation: 

Evaluate the distribution of selected variables using count plots to identify patterns and imbalances.
