# Cryptocurrencies Analysis

## Purpose
This repository contains code for clustering cryptocurrencies currently being traded based on certain features using machine learning techniques. The main goal is to group similar cryptocurrencies together for further analysis.

## Skills Used 
Python, Unsupervised machine learning (clustering)

## Actions 
In this project, the goal was to cluster cryptocurrencies based on certain features using machine learning techniques. The process began with data preprocessing, where the cryptocurrency dataset was loaded from a CSV file. This involved removing unnecessary columns, handling missing values, and converting data types to prepare the data for analysis. Additionally, categorical variables were transformed into numerical format using one-hot encoding, and the data was standardized using StandardScaler to ensure uniformity across features.

Following data preprocessing, dimensionality reduction was performed using Principal Component Analysis (PCA) to reduce the dataset to three principal components. This step aimed to capture the most significant variation in the data while reducing its dimensionality, making it more manageable for clustering.

The next step involved clustering the cryptocurrencies using the K-Means algorithm. The optimal number of clusters was determined using the elbow method, and the K-Means algorithm was applied with this optimal number. Cryptocurrencies were then assigned to clusters based on their features, and the resulting clusters were appended to the dataset.

I created a scatter plot to visualize the clusters, providing a comprehensive view of how cryptocurrencies are grouped based on their features. 

## Results 
In total, there are 532 cryptocurrencies being traded. Using the elbow curve technique, the ideal number of clusters was found to be 4. The majority of the cryptocurrencies were allocated to cluster 0 and 3. 

<img src="https://github.com/teresa-le/Cryptocurrencies/blob/main/Resources/Scatter%20Plot.png">
