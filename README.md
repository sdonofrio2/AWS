# Homework-13---AWS
For this homework I generated a report of what cryptocurrencies are available in the hypothetical trading market and grouped them using classification. 

I began by importing the csv file and preprossessing the data to reset the index, remove null values, etc. Next, I used PCA to reduce the dimensions of the data frame to 3 principal components. After this, I used the KMeans algorithm from sklearn to cluster the cryptocurrencies. Finally, I used hvplot to create some visualizations to present the final results. 