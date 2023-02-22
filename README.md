# Cryptocurrency Clustering

## Analysis Overview
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.\
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.\
Methods:
- preprocessing the database,
- reducing the data dimension using Principal Component Analysis,
- clustering cryptocurrencies using K-Means,
- visualizing classification results with 2D and 3D scatter plots.
<br><br>

## Resources
- Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3
<br><br>

## Results
Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.
<br><br>

### Clustering Cryptocurrencies using K-Means - Elbow Curve
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.\
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10. 
<p align="center">
    <img src="https://github.com/cmwardcode/Cryptocurrencies/blob/main/Images/Elbow%20Curve.png"> 
</p>
<br><br>

### Visualizing Cryptocurrencies Results
#### 3D-Scatter plot with clusters
<p align="center">
    <img src="https://github.com/cmwardcode/Cryptocurrencies/blob/main/Images/3D%20Scatter.png"> 
</p>
This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.
<br><br>

#### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply
<p align="center">
    <img src="https://github.com/cmwardcode/Cryptocurrencies/blob/main/Images/hvplot.scatter.png"> 
</p>
Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.
<br><br>

## Summary
Identification of the classification of 532 cryptocurrencies based on similarities of their features.\
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.
