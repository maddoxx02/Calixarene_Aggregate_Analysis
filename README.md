# Calixarene Aggregate Analysis

## Introduction

This repo presents the results of analysing aggregate behaviour of Calixarene group compounds (thiacalix[4]-crown-ethers) under various synthesis conditions. By varying the compound, solvent, mixture temperatures and concentration during the synthesis procedure, we acquire twelve individual films displaying different aggregate behaviour. Using a combination of machine learning, image segmentation and Data analysis, we explore the relation of synthesis conditions to the occurrence of aggregates on the surface of these films. These films with aggregates are primarily aimed at being used as drug carriers in medicine. This research aims to explore the underlying relation between the behaviour of aggregates & their properties with those of the synthesis conditions, therefore allowing theoretical prediction of aggregate properties before conducting complete chemical synthesis. Further, this repo consists of the Python code, generated results and data analysis performed on the results. 


## Methodology

![Analysis of Calixarene - Pipeline 1](Figures/Approach_1.png)
An overview of our experimental pipleline of aggregate analysis. The figure highlights the use of chemical descriptors along with atomic force microscopy features of synthesized films to analyse correlations and dependenceis within the synthesis procedure. 

![Analysis of Calixarene - Pipeline 2](Figures/Approach_2.png)
A Pipeline of aggregate analysis using regression models (Random Forest and Linear Regression) on data acquired from image segmentation from Cellpose Plus [2], Atomic force microscopy data and Chemical Descriptors from RD-KIT toolbox [3]. 

## Results 

...


## Code 

...

## Scientific Article (in-progress)
 We are currently preparing a complete version of our experiment aimed at publicaiton in scientific journals. [1] is a published work, showing the intial experiment that highlights groundworka and achieved progress on this experiment. 

## References

[1]: Chetinel, I. D., et al. "Control of Self-Organization of Thiacalix [4] Crown-Ethers in Cone and 1, 3-Alternate Forms in Nanofilms on Quartz Substrate." Colloid Journal 87.2 (2025): 236-245.

[2]: Huaman, Israel A., et al. "Cellpose+, a morphological analysis tool for feature extraction of stained cell images." arXiv preprint arXiv:2410.18738 (2024).

[3]: Landrum, Greg. "Rdkit documentation." Release 1.1-79 (2013): 4.
