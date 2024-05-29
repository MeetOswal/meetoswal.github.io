---
title: "Air Quality Index Predictor"
excerpt: " Task of implementing index sharding and selective search within a web search engine framework."
collection: portfolio
---
Objective
------
This project aimed to enhance web search engine performance through the implementation of index sharding and selective search. We utilized a carefully curated dataset and employed various clustering techniques to organize data into efficient structures for improved information retrieval.

Dataset and Tools
------
We used the Cohere/msmarco-v2-embed-english-v3 dataset from Hugging Face, which provides dense numerical representations of text data. The project was implemented using Python 3 and C++, leveraging libraries like Scikit-learn and NumPy for clustering and data analysis.

Clustering Techniques
------
Three clustering techniques were employed:
1. K-Means Clustering: This partitions data into K clusters based on the nearest mean, optimizing cluster assignments iteratively.
1. K-Means Mini-Batch Clustering: A variant of K-Means that processes subsets of data for faster convergence, suitable for large datasets.
1. Gaussian Mixture Models (GMMs): These model data as mixtures of multiple Gaussian distributions, allowing more flexible clustering.

Results and Analysis
------
The project involved a comparative analysis of clustering techniques to determine which configuration maximized recall. The results provided insights into the trade-offs between different clustering methods and the impact of the number of clusters on selective search outcomes

Keywords
------
Index Sharding, Selective Search, Clustering Techniques K-Means Clustering, Mini-Batch K-Means, Gaussian Mixture Models (GMMs), Information Retrieval, Distributed Systems

You can get the code [here](https://github.com/MeetOswal/SearchEngine/tree/main/Project)