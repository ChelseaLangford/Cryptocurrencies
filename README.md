# Cryptocurrency Analysis
The purpose of this analysis was to used an unspervised learning model and clustering algorithm to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a cliassification system to inform investments in the crypto market.

## Preprocessing the Data for PCA
- First, the data was preprocessed to remove unnecessary columns and remove rows with null values
- Next, the get_dummies() method was used to create variables for text features 
- Then, the StandardScaler fit_transform() function standardized the features in the updated dataframe

## Reducing Data Dimensions Using PCA and Clustering Using K-Means
- PCA was applied to reduce the dimensions to 3 principal components 
- Using the updated dataFrame with the PCA components, an elbow curve was created to find the best value for K
- The K-Means algorithm ran to make predictions of the K clusters for the cryptocurrency data

## Visualizing Results
- A 3D scatter plot was created using the scatter_3d() function to plot the three clusters and visualize the cyptocurrency classifactoins formed based on the model
