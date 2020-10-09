# Cryptocurrencies

This project's purpose was to help understand machine learning and use it with cryptocurrencies.  I used crypto data and then cleaned it to make it easier to analyze.  I then used  StandardScaler from sklearn to standardize all of the data from the X DataFrame.  This is required before we move to the PCA and K-Means Algorithm.  Then I used KMeans algorithm from sklearn to cluster the cryptocurrencies using the PCA data.  I did this by using a elbow curve to find the best k-value, and then I ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

Lastly, I visualized the data by using Plotly Express to create a 3d Scatter.  I then created a scatter plot using hvplot.scatter to present the clustered data about cryptocurrencies having x="TotalCoinsMined" and y="TotalCoinSupply" to contrast the number of available coins versus the total number of mined coins.
