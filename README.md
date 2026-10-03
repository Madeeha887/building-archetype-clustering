# building-archetype-clustering
Python code for building archetype identification using k-prototypes clustering, including cluster-number selection, parameter sensitivity, stability assessment, and comparison with alternative clustering methods.
This repository contains the Python code used for the clustering analyses presented in the study:Identifying building archetypes via combined morphological and façade characteristics: A k-prototypes approach
# Repository Contents
The repository contains two Jupyter notebooks. The notebooks are organised using section headings and comments corresponding to the main stages of the analytical workflow.
# k-prototypes clustering analysis
This notebook contains the main k-prototypes clustering workflow, including:
Data preprocessing
Determination of the number of clusters 
k-prototypes hyperparameter tuning 
k-prototypes clustering
Clustering evaluation 
Clustering stability 
# Comparative clustering analysis
This notebook contains the comparative assessment using alternative clustering methods, including: 
k-prototypes clustering
k-medoids clustering using Gower dissimilarity
Hierarchical agglomerative clustering using Gower dissimilarity
# Dataset 
The analysis uses a mixed-type building dataset comprising numerical and categorical variables. 
Numerical variables (Window-to-wall ratio (WWR), Aspect ratio (AR), Surface-area-to-volume ratio (SVR)
Categorical variables (Building height, Window type, Shading type) 
The dataset used in this study forms part of ongoing PhD research and is therefore not publicly available at this stage.
# Software Environment
The analyses were conducted in Jupyter Notebook (version 7.0.8) using Python.
The principal Python packages and versions used were:
NumPy 1.26.4
pandas 3.0.3
Matplotlib 3.10.9
kmodes 0.12.2
kneed 0.8.5
SciPy 1.13.1
scikit-learn 1.8.0
# Reproducibility
Random seeds are specified within the notebooks where applicable to support reproducibility.
The final K-prototypes configuration used in the study was:
Number of clusters: k = 4
Categorical weighting parameter (gamma): 0.5
Initialisation method: Huang
Number of initialisations (`n_init`): 30
Random state: 42

