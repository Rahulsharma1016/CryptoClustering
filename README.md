Cryptocurrency Clustering Analysis
This project involves clustering cryptocurrencies using K-means and Principal Component Analysis (PCA) to identify patterns in their performance.
The steps outlined below detail how to prepare the data, identify the optimal number of clusters (k), and visualize the results using Python's Scikit-learn and hvPlot libraries.

Find the Best Value for k Using the Scaled DataFrame
Use the Elbow Method:

Create a list of k-values ranging from 1 to 11.
Calculate the inertia for each value of k using a for loop.
Store these inertia values in a dictionary.

![image](https://github.com/user-attachments/assets/12b02385-5ef4-4acd-aa48-072a45e5533a)


Cluster Cryptocurrencies with K-means Using the Scaled DataFrame
Apply K-means:

Initialize and fit the K-means model using the scaled DataFrame and the optimal value for k.
Predict clusters and assign labels to each cryptocurrency.

![image](https://github.com/user-attachments/assets/540ddcf3-a97e-4afe-be8b-d90abdb6025e)


Resources
Python Libraries Used:
Scikit-learn
hvPlot
Pandas
Documentation References:
Scikit-learn Documentation
hvPlot Documentation
