 # Crypto Clustering Instructions

## Renaming File
1. Rename the `Crypto_Clustering_starter_code.ipynb` file as `Crypto_Clustering.ipynb`.

## Loading Data
2. Load the `crypto_market_data.csv` into a DataFrame.

## Summary Statistics and Data Plotting
3. Get the summary statistics and plot the data to visualize its structure before proceeding.

## Data Preparation
4. Use the `StandardScaler()` module from scikit-learn to normalize the data from the CSV file.
5. Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

## Finding the Best Value for k Using Original Scaled Data
6. Use the elbow method to find the best value for k.
7. Answer the question: What is the best value for k?

## Clustering Cryptocurrencies with K-means Using Original Scaled Data
8. Initialize the K-means model with the best value for k.
9. Fit the K-means model using the original scaled DataFrame.
10. Predict the clusters to group the cryptocurrencies using the original scaled DataFrame.
11. Create a scatter plot to visualize the clusters.

## Optimizing Clusters with Principal Component Analysis (PCA)
12. Perform PCA and reduce the features to three principal components.
13. Retrieve the explained variance and answer the question: What is the total explained variance of the three principal components?
14. Create a new DataFrame with the PCA data.

## Finding the Best Value for k Using PCA Data
15. Use the elbow method on the PCA data to find the best value for k.
16. Answer the questions: What is the best value for k when using the PCA data? Does it differ from the best k value found using the original data?

## Clustering Cryptocurrencies with K-means Using PCA Data
17. Initialize the K-means model with the best value for k.
18. Fit the K-means model using the PCA data.
19. Predict the clusters to group the cryptocurrencies using the PCA data.
20. Create a scatter plot to visualize the clusters and analyze the impact of using fewer features.
