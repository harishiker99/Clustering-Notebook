[
# Authorship Attribution using ML

Authorship Attribution is a task within# Text Clustering with KMeans, Hierarchical, and EM Clustering

Authorship Attribution is a task within the domain of Natural Language Processing (NLP) that aims to identify and attribute written texts to their respective authors based on linguistic patterns and style. This task is very intricate due to diverse writing styles, language nuances, and vocabulary differences exhibited by various authors. Despite its intricacies, authorship attribution has played a crucial role in identifying anonymous or disputed texts, attributing authorship to historical documents, and even unmasking authors in the digital realm.

## Overview
In this project, we explore text clustering techniques to group documents based on their linguistic patterns and style. We employ three main clustering algorithms: KMeans, Hierarchical, and Expectation-Maximization (EM) clustering. Additionally, we perform model selection to determine the champion clustering model and conduct error analysis on different vector embeddings to assess their effectiveness in representing textual data.

## Requirements
- `requests`
- `nltk`
- `pandas`
- `numpy`

Please refer to the `requirements.txt` file for specific version details of the libraries.

## Installation
To install the required dependencies, run:
 the domain of Natural Language Processing (NLP) that aims to identify and attribute written texts to their respective authors based on linguistic patterns and style. This task is very intricate due to diverse writing styles, language nuances, and vocabulary differences exhibited by various authors. Despite its intricacies, authorship attribution has played a crucial role in identifying anonymous or disputed texts, attributing authorship to historical documents, and even unmasking authors in the digital realm.

# Requirements
libraries used: requests, nltk, pandas, numpy
(Check the requirements.txt file for version details)

# Downloading the dependencies
pip install -r requirements.txt

## Usage
1. Ensure all dependencies are installed.
2. Run the Jupyter Notebook by executing:


# Running the jupyter notebook
3. Navigate to the notebook file for text clustering.

## Text Clustering Techniques
### 1. KMeans Clustering
KMeans clustering is a popular partitioning method that aims to divide the data into non-overlapping clusters.

### 2. Hierarchical Clustering
Hierarchical clustering builds a tree of clusters by recursively merging or splitting them based on their similarity.

### 3. Expectation-Maximization (EM) Clustering
EM clustering, also known as Gaussian Mixture Model (GMM) clustering, assumes that data points are generated from a mixture of several Gaussian distributions.

## Champion Model Selection
We evaluate the performance of each clustering algorithm and select the champion model based on specific evaluation metrics such as silhouette score or purity.

## Error Analysis for Vector Embeddings
We conduct error analysis for different vector embeddings including:
- TF-IDF
- Latent Dirichlet Allocation (LDA)
- Doc2Vec
- Bag of Words (BoW)

## Conclusion
Text clustering is a powerful technique for organizing large textual datasets. By employing various clustering algorithms and conducting thorough error analysis, we can gain insights into the underlying structures of the data and improve the effectiveness of our clustering models.

For detailed implementation and analysis, refer to the Jupyter Notebook included in this repository.

