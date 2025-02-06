Module 19 - Crypto Clustering Challenge

Project Overview:
Use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes, allowing for deeper insights into the behavior and trends of these digital assets.

Programming and Concepts Used:

* Software: Python, Jupyter Notebook
* Libraries: scikit-learn, pandas, hvplot, plotly

Analysis:

1) Prepare the data using StandardScaler() module from scikit-learn to normalize the data from the CSV file
2) Find the best value for k using the scaled dataframe using the elbow method
3) Cluster cryptocurriencies with K-Means using the scaled dataframe
4) Optimize clusters with principal component analysis (PCA)
5) Find the best value for k using the PCA dataframe
6) Cluster cryptocurrencies with K-Means using the PCA dataframe

Answer the following question:
What is the impace of using fewer features to cluster the data using K-Means?

Using fewer features to cluster data with K-Means can typically provide a clearer and more precise representation of the data, in this particular instance, both methods seem to yield very similar results. The outlier separation was more distinct with the K-Means analysis, but the results were similar overall.

The final analysis includes the following aspects:

* Preprocessing the data for PCA
![market data](market_data.png) 
* Reducing Data Dimensions using PCA
* Clustering cryptocurrencies using K-Means
* Visualizing cryptocurrencies results
![contrast elbow](contrast_elbow.png)
![contrast clusters](contrast_clusters.png)

Support Received: Xpert Learning, StackOverflow, Class Notes

