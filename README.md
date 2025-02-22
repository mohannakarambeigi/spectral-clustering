# spectral-clustering

## Table of contents
* [General info](#general-info)
* [Abstract](#Abstract)
* [Introduction](#Introduction)
## General info
This project utilizes spectral clustering techniques to analyze two datasets seperately. It includes the construction of k-nearest neighbor similarity graphs, eigenvalue-driven clustering, and comparative assessments against alternative clustering methods. Explore and understand complex datasets with this adaptable tool.

##  Absract
In machine learning and data analysis, spectral clustering is a prominent method for grouping datasets based on their inherent structures.
This study explores the application of spectral clustering to two different
datasets, Circle and Spiral, and compares its effectiveness against other
clustering algorithms.

## Introduction
Spectral clustering is a widely used unsupervised learning technique based on
spectral graph theory. It efficiently clusters data points in high-dimensional
spaces by projecting them onto a lower-dimensional space using the eigenvectors of a similarity graph’s Laplacian matrix. This method has been successfully
applied in fields such as image segmentation, community detection, and document clustering.
Clustering is a fundamental technique in unsupervised learning, where data
points are grouped based on their similarities. Broadly, clustering approaches
can be classified into two types: compactness-based clustering, where points in
close proximity are grouped together (e.g., K-Means Clustering), and connectivitybased clustering, which clusters points based on their relationships rather than
just proximity. Spectral clustering follows the connectivity-based approach,
making it suitable for identifying complex structures that traditional methods
struggle with.
In this study, we evaluate spectral clustering on two datasets, Circle.csv and
Spiral.csv. The implementation follows a structured approach: constructing
a similarity graph using a Gaussian kernel, computing the Laplacian matrix,
extracting eigenvectors, and performing clustering. This process helps analyze
spectral clustering’s effectiveness in handling non-linearly separable data.

