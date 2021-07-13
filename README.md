# Cryptocurrencies

## Purpose
The purpose of this analysis is to use unsupervised learning on cryptocurrencies to try to create a classification system for investors to use in an investment portfolio for customers.  

## Overview

The data was preprocessed which allowed it to be used in by PCA to reduce the demensions.  Using an elbow curve 4 was determined to be the best number of clusters to use.

![alt_tex](https://github.com/duckhang2210/Crypto-Data/blob/main/bokeh_plot.png)

This number of clusters was then used to run a KMeans clustering model and the 3-D scatter plot below is a visual of the results.

![alt_text](https://github.com/duckhang2210/Crypto-Data/blob/main/3dplot.png)

Finally the MinMaxScaler was used to scale the TotalCoinsMined and TotalCoinSupply columns which the relationship between the two is shown below by class.

![alt_text](https://github.com/duckhang2210/Crypto-Data/blob/main/bokeh_plot_chart)
