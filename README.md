# Customers-Segmentation-Kmeans
![download (1)](https://github.com/anjalikhushi/Customer-Segmentation-Project/assets/82653640/9303bbc2-7907-474b-a214-20c44e220fa3)

 ### Introduction:
Customer segmentation is a crucial strategy for businesses aiming to understand their customer base and tailor their marketing efforts accordingly. In the context of a shopping mall, segmentation can help identify groups of customers with similar behaviors and preferences, allowing for more targeted promotions, personalized services, and improved customer satisfaction. One of the most popular techniques for customer segmentation is K-means clustering.

### Data Description: 
1.Gather Data: Collect customer data. For this example, let's assume we have a dataset with the following columns: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100).

2.Clean Data: Ensure the dataset is clean (e.g., no missing values).

### Exploratory Data Analysis: 
Exploratory Data Analysis (EDA) is a crucial step in any data science project, including customer segmentation using K-means clustering. EDA helps to understand the data, detect patterns, spot anomalies, and form hypotheses.

### Customer Segmentation: 
K-means clustering is an unsupervised machine learning algorithm that partitions a dataset into K distinct, non-overlapping subgroups (or clusters) based on feature similarity. The algorithm works as follows:

Initialization: Randomly select K initial cluster centroids.

Assignment: Assign each data point to the nearest centroid based on the Euclidean distance.

Update: Recalculate the centroids as the mean of all data points assigned to each cluster.

Repeat: Repeat the assignment and update steps until the centroids no longer change significantly or a predefined number of iterations is reached.

#### Why Use K-Means for Mall Customer Segmentation?
Simplicity and Efficiency: K-means is easy to implement and computationally efficient, making it suitable for large datasets.

Interpretability: The resulting clusters can be easily interpreted, providing clear insights into customer segments.

Scalability: K-means scales well to large datasets, allowing it to handle the diverse and extensive data typically available in a mall setting.


# About Data:
 CustomerID: This is a unique identifier for each customer in the dataset.
 
 Gender: This indicates the gender of the customer, with 'Male' or 'Female' as the possible values.
 
 Age: This indicates the age of the customer in years.
 
 Annual Income (k$): This indicates the annual income of the customer in thousands of dollars.
 
 Spending Score (1-100): This is a score assigned to the customer based on their spending behavior, with 1 being the lowest score and 100 being the highest score. This score is typically 
 calculated based on factors such as the customer's spending habits, frequency of purchases, and total amount spent.
 
Together, these features can be used to analyze and segment customers based on their demographic and spending behavior. For example, we could use clustering algorithms to group customers based on similar age, income, and spending patterns, which could then be used to develop targeted marketing strategies or product recommendations.


# Steps:
1) Import the data into a data analysis tool such as Python or R.
2) Check the data types and missing values.
3) Use descriptive statistics such as mean, median, and standard deviation to understand the central tendencies and spread of the different variables.
4) Visualize the distribution of the variables using histograms or box plots.
5) Analyze the correlation between different variables using a correlation matrix or scatter plot.
6) Finding the optimal number of clusters using Elbow Method.
7) Use clustering algorithms such as k-means to segment customers based on their demographic and spending behavior.
8) Visualize the results of the clustering analysis using a scatter plot or heat map.
9) Draw conclusions and insights from the analysis, and present them in a report format.
