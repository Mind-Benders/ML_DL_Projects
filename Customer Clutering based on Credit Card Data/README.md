<div align = 'center'>
  <h1>Customer Clustering based on Credit Card Data</h1>
</div>

### Problem Statement

Build the model to cluster the Customers based on data such as Balance, Balance frequency, Purchases, One-off purchases, Installment Purchases, Cash advance, Purchases frequency, One-off purchases frequency, Purchases installment frequency, Cash advance frequency, Cash advance trx, Purchases trx, Credit Limit, Payments, Minimum payments, PRC full payment, and Tenure. 

### Dataset

The dataset for this project is taken from the Kaggle. 
Here is the link for the dataset: https://www.kaggle.com/code/kashish2212/clustering-k-means-yellowbrick-dendrogram/data that was used.

### What Have I Done?

- Imported all the required libraries and dataset for this project.
- Described the data
- Checked for the missing/null values in the dataset
- Dropped the unnecessary columns
- Visualized the patterns based on the features
- Built the K-means Clustering model with following methods
    - Distortion method
    - Silhouette method
    - Calinski Harabasz method
    - WCSS (Within Cluster Sum of Squares) method
- Checked for optimal number of Clusters
- Built the KMeans model with optimal no of Clusters
- Predicted the Cluster the number for the existing dataset
- Scatter plotted between BALANCE column and CREDIT_LIMIT column with color of their respective cluster

### Libraries Used:

- Pandas
- Plotly
- Numpy
- Sklearn
- Yellowbrick
- Matplotlib

### Some Visualizations
![image](https://user-images.githubusercontent.com/87692393/196041418-101e741a-23ef-4440-aeac-dad685aa7b9b.png)
![image](https://user-images.githubusercontent.com/87692393/196041433-65c9e21d-08da-4017-aa47-4d9123ddfa35.png)
![image](https://user-images.githubusercontent.com/87692393/196041443-c004137b-5092-4ffe-85a5-3e1510f54e50.png)
![image](https://user-images.githubusercontent.com/87692393/196041798-c1b6714b-da2b-4b3c-99db-c631756051c7.png)

## Conclusion

From the above plot, We can conclude that we clustered the customers based on their features (i.e., payments, credit limits, etc.) and in future, anyone can apply other approaches such as hierarchical clustering to get optimal no of clusters.

### Author

Code Contributed by: Ganesh Utla

Github: [ganesh-utla](https://github.com/ganesh-utla)
