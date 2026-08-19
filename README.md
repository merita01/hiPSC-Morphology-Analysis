
Large-Scale Quantitative Characterization of hiPSC Colony Morphology

This project analyses human induced pluripotent stem cell (hiPSC) colony morphology using image processing, statistical analysis, and machine learning.

Microscopy segmentation data was used to extract individual colonies and measure different aspects of their morphology. The final dataset contained **2,474 microscopy images and 69,714 colony objects**.

The analysis followed this workflow:

Image segmentation, Colony extraction, Morphological feature extraction, PCA, K-Means clustering, Statistical analysis

Analysis

Nine morphological features were extracted for each colony, including area, perimeter, eccentricity, solidity, extent, axis lengths, convex area, and equivalent diameter.

PCA was used to look at the main patterns in the data, followed by K-Means clustering to see whether colonies could be grouped based on their morphology. The elbow method and silhouette analysis were used to help choose the number of clusters, with **K = 2** selected for the final analysis.

Repository

The repository contains the Jupyter notebooks used for the analysis and the completed research paper.

The original microscopy dataset and the full extracted dataset are not included.


