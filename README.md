# CryptoClustering
Bootcamp Module 19 Challenge

The files contained in the CryptoClustering repository were created as an educational bootcamp project to use Python and unsupervised learning to predict cryptocurrencies are affected by 24-hour or 7-day price changes. This project requires the import of pandas, hvplot, scikit-learn to run. The crypto_market_data.csv file can be found in the Resources folder. 

![data](./Resources/crypto_plot.png)

To prepare the data from the csv file it was scaled for anlaysis. I created elbow plots to find the best k value for the data and then K-means to cluster the data into a scatter plot. 

![elbow](./Resources/elbow_curve.png)

![scatter](./Resources/scatter_plot.png)

The clusters were then optimized using Principal Component Analysis and I repeated the elbow plot and scatter plot visualizations to then compare the two sets of visializations. 

![pca_elbow](./Resources/pca_elbow_curve.png)

![pca_scatter](./Resources/pca_scatter_plot.png)


References: The fictional data used in this project was created by edEx Boot Camps LLC for educational purposes only.

The starter file contained in the Resources folder was used as a starting point for the Jupyter Notebook file.

The website: https://holoviz.org/tutorial/Composing_Plots.html was reviewed to compose the two plots and stack them in a single column. 

