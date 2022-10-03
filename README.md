# tumor-classification
The objective of this project is to propose and compare machine learning clustering methods (k-means, Gaussian Mixture Model) and dimension reduction techniques (PCA, MDS) to classify different types of cancers based on gene expression.

Genome sequencing has allowed great medical advances in recent years. In particular, we can now use RNA sequences to identify the presence of cancer.

The data used in this project is comes from gene expression data of different types of cancers. We are working on a dataset extracted from the synapse database  (Weinstein, John N., et al. 'The cancer genome atlas pan-cancer analysis project.' Nature genetics 45.10 (2013): 1113-1120. https://www.nature.com/articles/ng.2764.pdf?origin=ppub) and which concerns 5 types of tumors.

This dataset is made of two files, one that contains the gene expressions (20531 variables for 801 individuals) and the other that contains the type of cancer associated with each 801 individual (row of the first table).

Outline:
* Run the k-means algorithm, and compare the resulting classificaiton to the Cancer labels through a confusion matrix.
* Run the k-means on the first n components/axis of the outputs of a PCA.
* Run the GMM algorithm, and compare the resulting classification to the Cancer labels using a confusion matrix.
* Run the GMM algorithm on the first n components/axis of the outputs of a PCA.
* Do at all over agains, but with MDS.


3. Compare the clustering results to each other (by computing the number of well classified examples) and discuss the results.

Code, processes and results can be found in the notebook file.
