## Authors
- Yarin Arava
- Yuval Galula
  
# MNIST Clustering with K-Means and GMM

Unsupervised learning project exploring how clustering algorithms
represent the structure of handwritten digits in the MNIST dataset.

## Methods

- Exploratory Data Analysis (EDA)
- K-Means clustering
- Gaussian Mixture Models (GMM)
  - Full covariance
  - Diagonal covariance
- Cluster-to-digit mapping using majority voting
- Cluster distribution and centroid visualization
- Comparison of different numbers of clusters

## Key Findings

- K-Means produced clearer and more decisive digit clusters than the tested GMM configurations.
- Visually similar digits were often grouped or split across multiple clusters.
- Increasing the number of clusters helped capture different writing styles within the same digit class.
- Full-covariance GMM was considerably more computationally expensive than diagonal GMM and K-Means.

## Technologies

Python, NumPy, scikit-learn, Matplotlib, Seaborn
