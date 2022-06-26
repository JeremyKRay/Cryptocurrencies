# Cryptocurrencies
## Overview
The purpose of this project was to analyze a large dataset of cryptocurrencies for Accountability Accounting. They want to include a new cryptocurrency investment portfolio for customers interested in the cryptocurrency market. There are many cryptocurrencies out there and not all are even being actively traded. Accountability Accounting wants a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment portfolio. 

## Procedure
### Preprocessing
First, some preprocessing of the data was completed. Data was removed from cryptocurrencies that weren't being traded. Unnecessary columns and rows with null values were removed. Only data on cryptocurrencies with working algorithms was kept; in this case, all of them had working algorithms. And finally, only cryptocurrencies where coins have been actually mined were kept. This narrowed a dataset with 1252 cryptocurrencies down to 532.

![preprocessing.png](https://github.com/JeremyKRay/Cryptocurrencies/blob/f668993fb75cb06c4bb164e6f225a6dd3cce519d/Images/Preprocessing.png)

### PCA
Second, PCA was used to reduce dimensions to 3 principal components.

![PCA.png](https://github.com/JeremyKRay/Cryptocurrencies/blob/b675aeb0d0b0535cbfcda3d37095882eb60ea641/Images/PCA.png)

### Clusters
Third, clusters were created to group the cryptocurrencies currently in the trading market. An elbow curve was created to come up with the best value for K. The K value was then used to classify the various cryptocurrencies.

![Elbow_Curve.png](https://github.com/JeremyKRay/Cryptocurrencies/blob/c141db74fa99513a970ace2127c4c08a9516a6e0/Images/Elbow_Curve.png)

### Visualizations
Fourth, hvplot and pplot were used to create a finalized table and visualizations.

![3d_pplot](https://github.com/JeremyKRay/Cryptocurrencies/blob/c4f56fadb7b39e923fa31a1fbf202a8fded833a2/Images/3d_pplot.png)
![Final_Table](https://github.com/JeremyKRay/Cryptocurrencies/blob/3c15257896c55868e9938c2e5dde0ba43bd86084/Images/Final_Table.png)
![Final_hbplot_scatter](https://github.com/JeremyKRay/Cryptocurrencies/blob/d8b5ad354176383dfbbe15c14d8bad77c284cb12/Images/Final_hvplot_scatter.png)

## Results
Cryptocurrencies can be classified into 4 different categories, it appears. With 2 that are fairly closely grouped, and 2 that appear to be somewhat outliers. If I was an investment group, I would focus on classes 0 and 1. But, I do not know a whole lot about cryptocurrency so I would not listen to me. A professional should look at this model, and investors should listen to their conclusion on what it is showing. 
