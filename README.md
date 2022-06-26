# Cryptocurrencies
## Overview
The purpose of this project was to analyze a large dataset of cryptocurrencies for Accountability Accounting. They want to include a new cryptocurrency investment portfolio for customers interested in the cryptocurrency market. There are many cryptocurrencies out there and not all are even being actively traded. Accountability Accounting wants a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment portfolio. 

## Procedure
### Preprocessing
First, some preprocessing of the data was completed. Data was removed from cryptocurrencies that weren't being traded. Unnecessary columns and rows with null values were removed. Only data on cryptocurrencies with working algorithms was kept; in this case, all of them had working algorithms. And finally, only cryptocurrencies where coins have been actually mined were kept. This narrowed a dataset with 1252 cryptocurrencies down to 532.

### PCA
Second, PCA was used to reduce dimensions to 3 principal components.

### Clusters
Third, clusters were created to group the cryptocurrencies currently in the trading market. An elbow curve was created to come up with the best value for K. The K value was then used to classify the various cryptocurrencies.

### Visualizations
Fourth, hvplot and pplot were used to create a finalized table and visualizations.

## Results

