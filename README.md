# Customer Segmentation Using K-Means Clustering
This project focuses on customer segmentation using K-Means clustering. The goal is to group customers based on their purchasing behavior, complaints, and money spent.
# Dataset
The dataset consists of random data for 100 customers. It includes the following features:

customer_id: Unique ID for each customer.

products_purchased: The number of products purchased by the customer.

complaints: The number of complaints made by the customer.

money_spent: The total amount of money spent by the customer.

The data is saved in a CSV file named customer_data.csv and generated using NumPy.

# Workflow
Data Preparation:

The dataset is generated and stored in a Pandas DataFrame.
Basic exploratory analysis is done, such as displaying the first few rows and checking for missing values.
Feature Scaling:

The features are scaled using StandardScaler from Scikit-learn to standardize the data for clustering.
Clustering:

K-Means clustering is performed using 5 clusters (n_clusters=5).
The resulting clusters are stored in a new column named Cluster in the DataFrame.
Visualization:

A scatter plot is generated using Matplotlib to visualize customer segments, where:
X-axis represents the number of products purchased.
Y-axis represents the number of complaints.
Colors represent different clusters.
