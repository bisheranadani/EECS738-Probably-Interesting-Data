# EECS738-Probably-Interesting-Data
This repository holds Vivek Tallavajhala and Bisher Anadani's EECS 738 Project one. The requirements for the project are as below:

Probably Interesting Data
Distribution estimation
1. Set up a new git repository in your GitHub account
2. Pick two datasets from
https://www.kaggle.com/uciml/datasets
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how machine learning can be used to
model distributions within the dataset
5. Build a heuristic and/or algorithm to model the data using
mixture models of probability distributions
programmatically
6. Document your process and results
7. Commit your source code, documentation and other
supporting files to the git repository in GitHub

The two datasets we chose were the iris dataset and the auto-mpg dataset. To use machine learning to model the data, we decided to implement the K-means algorithm, and then test the algorithm on both datasets. For each dataset, we performed basic feature engineering through heatmaps and histograms. In doing so, we could select attributes that would work well for clustering the data using K means. Further documentation can be found in the Jupyter notebook.

Note: FeatureEngineering.ipynb notebook used for feature engineering and kmeans.ipynb for implementation.

Using http://benalexkeen.com/k-means-clustering-in-python/ as a reference for K means implementation
