# small-molecule-partitioning
Code for https://doi.org/10.1101/2022.12.19.521099

Updated December 2022, Hanna D. Clements

## overview
All files should be located a single directory. If necessary, use the environment file for relevant programs; the input files (Excel) and code (as Jupyter Notebooks) needed to reproduce this study are briefly summarized here:

- small-molecule-partitioning.yml: Environment file for code used in this study
- QikProp_UMAP_input.xlsx: Excel file containing the small molecule QikProp descriptors for constructing chemical space and conducting clustering analysis 
- QikProp_modeling_input.xlsx: Excel file containing the small molecule QikProp descriptors for statistical modeling
- UMAP_clustering.ipynb: Code for uniform manifold and approximation (UMAP) dimensionality reduction and chemical space with associated clustering analysis
- modeling.ipynb: Code for all statistical models used in this study


## citation
This code is released under the MIT license. Commercial use, Modification, Distribution and Private use are all permitted. The use of this workflow can be acknowledged with the following citation:

Thody, S. A.; Clements, H. D.; Baniasadi, H.; Lyon, A. S.; Sigman, M. S.; Rosen, M. K. Small Molecule Properties Define Partitioning into Biomolecular Condensates. bioRxiv 2022, 2022.12.19.521099. https://doi.org/10.1101/2022.12.19.521099.

## contributors
- modeling.ipynb: Adapted from code by Iris Guo and Tobias Gensch with contributions from Ellyn Peters
- UMAP_clustering.ipynb: Adapted from code by Cian Kingston
