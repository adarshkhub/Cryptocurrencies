# Cryptocurrencies

### Software

-Python 3.7
-Jupyter Notebook 
   Libraries: Sk-learn, Plotly, Pandas

## Overview

Accountability Accounting is interested in breaking into the cryptocurrency market, but they have no idea how to get started. In order to learn more about Crypto they've asked us to apply our skills with unsupervised machine learning in order to try to find value in the crypto dataset they have provided. The goal is to attempt this by first preprocessing the data, reducing data dimensions using PCA, then applying K-Means to cluster the cryptocurrencies and finally provide a nice visual report for Accountability Accounting to understand the information we've gathered.


## Process/Results


###Preprocessing the data
In order to get the data ready for the algorithm, we clean up colums and rows that won't be applicable, create numerical variables for text features so that it can pass through the algorithm, and scale the data using StandardScaler.


###Reducing Data Dimensions Using PCA
While PCA itself is pretty complex mathematically, we can apply it by simply importing it from the sk-learn library.

###Clustering the Cryptocurrencies using K-Means
Using the elbow curve, we find that k=4 seems to be optimal.

###Visualizing the Cryptocurrency Results

In order to display the data in an easier to interpret way, we created a 3-D scatterplot.
