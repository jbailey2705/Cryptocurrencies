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

**Clustering Cryptocurrencies using K-Means - Elbow Curve**

We are using unsupervised machine learning to help us identify clusters of the cryptocurrencies.
We produced the following elbow curve below using the `K-Means` method iterating on k values from 1 to 10.

`Running K-Means with k=4`

![elbow_curve](https://user-images.githubusercontent.com/109354592/204948681-a9eb97f8-d36a-4cc2-a128-98022ab055db.png)

The best k value appears to be 4 so we would conclude on an output of **4 clusters** to categorize the crytocurrencies.

**Applying the Principal Component Analysis**

![dataframe_after_PCA](https://user-images.githubusercontent.com/109354592/204949248-bf06db9f-fb52-459c-a83d-ae8f4072151a.png)

**Visualizing Cryptocurrencies Results with 3D-Scatter plot with clusters**

![3D_model](https://user-images.githubusercontent.com/109354592/204949361-d9e2ef7f-7eb8-4509-8113-c2295b9676f0.png)

3-D scatter plot was generated using the `PCA algorithm`, reducing the crytocurrencies dimensions down to three principal components.

**Number of Tradable Cryptocurrencies****

![number_of_tradable_cryptos](https://user-images.githubusercontent.com/109354592/204949662-8614d841-23c0-4acf-97a2-a3670be2e031.png)

**DataFrame to plot results**

![dataframe_for_Cryptos](https://user-images.githubusercontent.com/109354592/204949753-4f334f2c-956e-4169-aa99-49c0136a8207.png)

**Tradable Cryptocurrencies**

![tradable_crypto_results](https://user-images.githubusercontent.com/109354592/204949863-192b1f52-4880-49eb-b1f7-215d200bb804.png)

## Summary
We've identified the classification of 532 cryptocurrencies based on their feature similarities.
Each group will need to be analyzed to determined, performance and potential interest for the investment banks potential clients.


