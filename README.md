# CryptoClustering
This challenge uses unsupervised learning to cluster similar data points together. The original data showed the percentage of change in crypto coin prices over various periods of time. 

The first step is to scale the data to make sure all the data points are on the same scale, which makes it so the algorithm doesn't have bias. We use the StandardScale() from sklearn.preprocessing.

The next step is to find out how many clusters the data should be grouped into. I used KMeans from sklearn to find the number of clusters, and then find the central point of each cluster and plot them using hvplot.

The same process is repeated after using Principle Component Analysis.