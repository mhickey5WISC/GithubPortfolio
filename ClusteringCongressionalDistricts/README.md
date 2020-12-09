This project was my contribution of an open ended final project for a Machine Learning grad school class at University of Wisconsin-Madison.

The objective of this analysis is to explore how different clustering methods could be appllied to automatically determine Congressional boundaries in the state of Wisconsin. The drawing of Congressional boundaries is notoriously influenced by partison bias. Unsupervised machine learning methods such as K-means, and Meanshift clustering could be applied to weighted Census tract data in order to automate this process, and potentially eliminate human influence.

This exploratory analysis reconciles the bounds of the problem at hand - a set number of clusters, each of which must be roughly equal in size. Neither the K-Means nor the Meanshift clustering algorithms ensure solutions with roughly equal sized clusters - therefore, the K-Means algorithm was redesigned to achieve this effect.

While this analysis sheds light on the limits of clustering algorithms, and involves the implementation of an altered K-means algorithm - the results are not deterministic. That is, an individual could run this algorithm over and over and get different results. This also means that human bias is not removed from the process.
