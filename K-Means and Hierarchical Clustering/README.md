# Clustering Algorithms

## Overview

This project focused on implementing and evaluating two popular clustering algorithms: K-Means and Hierarchical Clustering. The objectives were to gain hands-on experience with these unsupervised learning techniques and apply them to different datasets. Key achievements include:

- Implemented the K-Means and K-Means++ algorithms from scratch
- Applied K-Means clustering to synthetic data and image compression tasks
- Utilized Hierarchical Clustering with Ward's linkage on a customer dataset
- Visualized and analyzed the clustering results using various plotting techniques

## Datasets

### Synthetic Data

- Generated using `make_blobs` function from scikit-learn
- 300 instances with 4 clusters and a standard deviation of 0.6

### Image Data

- RGB image data for demonstrating image compression

### Mall Customer Data

- Dataset containing information about mall customers
- Used for Hierarchical Clustering to identify customer segments

## K-Means Clustering

The K-Means algorithm was implemented from scratch, with both the standard initialization and the K-Means++ initialization methods. The algorithms were applied to the synthetic data, and the clustering results were visualized using scatter plots. Key steps included:

1. Data generation and visualization
2. Implementation of K-Means and K-Means++ algorithms
3. Fitting the models with different random seeds
4. Plotting and comparing the clustering results

## Image Compression with K-Means

K-Means clustering was applied to an RGB image dataset to demonstrate image compression. The pixel values were treated as data points, and the algorithm identified the optimal centroids (compressed colors) to represent the image. The compressed and original images were displayed for visual comparison.

## Hierarchical Clustering

Hierarchical Clustering with Ward's linkage was implemented and applied to the Mall Customer dataset. The dendrogram was plotted to visualize the hierarchical structure of the clusters. Additionally, the identified customer segments were plotted and labeled based on their characteristics.

## Results and Observations

The project successfully demonstrated the implementation and application of K-Means and Hierarchical Clustering algorithms. The clustering results were visualized and analyzed, providing insights into the strengths and limitations of each technique. Key observations and findings were documented in the project report.

## Conclusion

This project provided valuable hands-on experience with popular clustering algorithms, including K-Means and Hierarchical Clustering. By implementing these algorithms from scratch and applying them to diverse datasets, a deeper understanding of unsupervised learning techniques was gained. The project showcased the effectiveness of clustering algorithms in various domains, such as data exploration, image compression, and customer segmentation.