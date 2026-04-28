## Description of Files

### Data_processing.ipynb
Performs data cleaning, handles missing values, and prepares features for clustering.

### Clustering Notebooks
Each notebook implements a different clustering algorithm and evaluates its performance:
- K-Means  
- Agglomerative Clustering  
- Gaussian Mixture Model (GMM)  
- Spectral Clustering  
- Self-Organizing Map (SOM)  

### Datasets
- `clean_data.csv`: Final cleaned dataset used for modeling  
- `pca_data.csv`: Dataset after dimensionality reduction using PCA  
- `global_baseline.csv`: Global reference data for benchmarking  
- `facility_baseline.csv`: Cluster-level benchmarking dataset  

## Workflow
- Data preprocessing and cleaning  
- Dimensionality reduction using PCA  
- Application of multiple clustering techniques  
- Evaluation of clustering performance  
- Benchmarking using cluster-based comparisons  


## Note
The original dataset was not uploaded to this repository due to its large file size.
