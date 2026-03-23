# HNSCC Transcriptomic Subtyping via UMAP and Clustering

This notebook performs:

- Gene filtering based on expression and variance  
- PCA dimensionality reduction  
- UMAP embedding optimization  
- Multiple clustering approaches:
  - HDBSCAN  
  - k-means  
  - Hierarchical clustering  
  - Gaussian Mixture Models  

---

## Environment Setup

Before running this notebook, create the required **conda environment** using the provided `environment.yml` file. This ensures that all required package versions are installed and that the analysis is reproducible.

From the root directory of this repository, run:

    conda env create -f environment.yml

Activate the environment:

    conda activate transcriptomic_clustering

Then launch Jupyter:

    jupyter notebook

Open the notebook and run it within this environment.