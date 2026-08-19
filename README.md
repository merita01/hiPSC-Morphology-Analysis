
Large-Scale Quantitative Characterization of hiPSC Colony Morphology


The project investigates human induced pluripotent stem cell (hiPSC) colony morphology using image processing, statistical analysis, and machine learning.

Microscopy segmentation data was processed to extract individual colony objects and quantify their morphology. The final dataset contained 2,474 microscopy images and 69,714 colony objects.

The analysis followed the workflow:

"Image segmentation ,Colony extraction ,Morphological feature extraction , PCA , K-Means clustering , Statistical analysis"

Analysis

Nine morphological features were extracted for each colony, including area, perimeter, eccentricity, solidity, extent, axis lengths, convex area, and equivalent diameter.

PCA was used to examine morphological variation, followed by K-Means clustering to identify morphological groupings within the dataset. Elbow and silhouette analysis were used to evaluate the clustering structure, with K = 2 selected for the final analysis.


Repository

The repository contains the Jupyter notebooks, generated figures, and completed research paper documenting the analysis.

The original microscopy dataset and complete extracted dataset are not included.

