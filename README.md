# schizomida

These scripts are related to the collection and analysis of shape outline information for schizomids conducted in R. They include reading in the shapes and information file as well as scripts for using existing packages for Fourier analysis, PCA, allometry, morphospace plotting, disparity-diversity correlation, and Gaussian mixture modelling. If you use these scripts for an academic work, please cite:

Kallal, R.J., de Miranda, G.S., Garcia, E.L. et al. Patterns in schizomid flagellum shape from elliptical Fourier analysis. Sci Rep 12, 3896 (2022). https://doi.org/10.1038/s41598-022-07823-y

https://www.nature.com/articles/s41598-022-07823-y#citeas


outline_analysis: This is the basic pipeline with data input, Fourier analysis, and disparity.

allometry_analysis: This script has the comparison of shape and centroids for the scaled dataset.

caribbean_only: This script is as outline_analysis but reduced for taxa from Caribbean islands.

cub_only: This script is as outline_analysis but reduced for Cuban taxa exclusively.

diversity_vs_disparity: Pearson correlations

clustering: Gaussian clustering analysis.
