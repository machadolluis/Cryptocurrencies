# Cryptocurrencies

## Overview

This project analyzes cryptocurrency data and utilizes unsupervised machine learning to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for new investments. 

 - To start, we preprocess the data to ensure the models work as intended;
 - Next, we reduce the dimensions of the data using PCA;
 - After that, using the K-Means clustering model, we classify the data;
 - Finally, we plot the results and visualize the classifications.

## Results

After preprocessing the data, we see that we are working with 532 tradable cryptocurrencies. 

From the Elbow Curve shown below, it is best to divide our K-Means model in 4 clusters.
![](/Resources/elbow_curve.png)

### Visualizing Data

* 3D scatter plot with clusters
![](/Resources/3d_scatter.png)

* Total Coins Mined vs. Total Coins Supplied 
![](/Resources/hvplot.png)
This graph does not efficiently differentiate the classes for the coins. Looking at the Tradable Coins Table, the only coin in class 2 is BitTorrent.

## Summary

After identifying the classification of the 532 tradable cryptocurrencies based on their similar features, it is now needed to analyze each distinct group to determine their performance and potential interest of the bank's clients.
