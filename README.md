# Cryptocurrencies

## Analysis Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.

We've used the following methods for the to complete our analysis:

  * preprocessing the database
  * reducing the data dimension using Principal Component Analysis
  * clustering cryptocurrencies using K-Means
  * visualizing classification results with 2D and 3D scatter plots

## Resource

 * `Jupyter Notebook 6.5.2`
 * [crypto_data.csv](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_18/crypto_data.csv)
 * [crypto_starter_code.ipynb](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-online/module_18/crypto_clustering_starter_code.ipynb)
 
## Results

The imported DataFrame before cleaning showed 1252 rows of data:

![dataframe_before_cleaning](https://user-images.githubusercontent.com/109354592/204948125-3dd6cc0d-fa05-43de-9398-d01ce800e1ab.png)


List of tradable cryptocurrencies after cleaning, 532 rows of data:

![dataframe_after_cleaning](https://user-images.githubusercontent.com/109354592/204948344-b8463539-e4d1-46d6-a133-2fc67432895d.png)

## Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

