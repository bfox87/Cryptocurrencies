# Cryptocurrencies Analysis

## Overview:
One of our most important clients, Accountability Accounting, is planning to offer a new cryptocurrency investment porfolio. They've tasked us with creating a report and classification system for currencies on the crypto trading market. Unsupervised machine learning methods will be used since there are not any known outputs we are predicting.

## Process:
 - To begin, the dataset was first preprocessed (fields dropped, text fields changed, features standardized) to so it could then be used in Principal Component Analysis or PCA.

 - Using PCA, the dataset dimensions were reduced to three principal components, thereby speeding up our machine learning process. The K-means clustering algorithm was used to group the currencies.

 - An elbow curve plot was first created to determine that four K clusters would be ideal.
![Elbow_Curve](https://github.com/bfox87/Cryptocurrencies/blob/main/Screenshots/Elbow_Curve.PNG)

 - After the K-means model was run, a 3D-scatter plot was utilized to visualize the PCA data and clusters.
![3D_Scatter](https://github.com/bfox87/Cryptocurrencies/blob/main/Screenshots/3D_Scatter.PNG)

 - A table of the 532 tradable cryptocurrencies was created showing which class they fall into. This table will be an integral part of the report to Accountability Accounting.
![tradable_table](https://github.com/bfox87/Cryptocurrencies/blob/main/Screenshots/tradable_table.PNG)

 - A scatter plot showing the relationship between a scaled Coin Supply and Coins Mined was also created.
![2D_Scatter](https://github.com/bfox87/Cryptocurrencies/blob/main/Screenshots/2D_Scatter.PNG)