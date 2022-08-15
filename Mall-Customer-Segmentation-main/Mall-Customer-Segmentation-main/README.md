# Mall-Customer-Segmentation
## Project Description
The purpose of this project is to cluster customers in a mall into multiple groups on the basis of age, spending capability, spending score etc. This can provide us useful insights into what are the requiremetns of each group and accordingly marketing strategies and policies can be built to optimize spending score of the customers. 

## Tools Used:
1. Scikit learn library in python for implementing clustering algorithms.
2. Pandas, numpy and matplotlib for data visualization and plotting.
3. Plotly for generating interactive graphs

## Data
Data has been taken from kaggle dataset Mall Customer Segmentation Data, corresponding csv file is present in Data folder of this repo. Link to download data: 
https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python/download

## Data Visualization
1. Histogram of individual features like age,sex, customer income and spending score is plotted to get idea of distribution.
2. Correlation and heat map are plotted to identify dependency between different features.
3. Pie chart is used to identify percentage of male vs female customer count.
4. Bivariate analysis between gender vs. annual income and spending score using violin plot and box plot respectively.

## Clustering Algorithms Implemented
1. **Elbow technique** is used to find optimal number of customers and clusters are generated using **K-means** clustering.
2. **Hierarchial** is used for generating clusters, optimal number of clusters is obtained using **Dendogram** method.

## Conclusion
By looking at the clusters of customers and their corresponding spending scores, customers have been aggregated them into 4 different categories namely Usual Customers, Priority Customers, Senior Citizen Target Customers, Young Target Customers. Appropriate marketing strategies and policies (according to segment in which custome lies) can be made to optimize the spending scores of the customer in the Mall.




