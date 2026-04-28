Description of Files
Data_processing.ipynb
Handles missing values, feature selection, and prepares the dataset for clustering.
Clustering Notebooks
Each notebook applies a different clustering algorithm and evaluates performance:
  -K-Means
  -Agglomerative
  -GMM
  -Spectral
 - SOM
Datasets
  -clean_data.csv: Final cleaned dataset
  -pca_data.csv: Reduced feature space after PCA
  -global_baseline.csv: Used for global comparison
  -facility_baseline.csv: Used for benchmarking at cluster level
Workflow
  -Data preprocessing and cleaning
  -PCA for dimensionality reduction
  -Apply multiple clustering techniques
  -Evaluate clustering performance
  -Perform benchmarking using cluster-based comparisons
Note that we werwenot able to upload the original data and processed data files as they are big 
