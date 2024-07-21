Customer Segmentation Using K-means Clustering

Table of Contents

-Overview
-Dataset
-Project Workflow
-Installation
-Visualization
-Contributing

Overview:
-Customer segmentation helps businesses understand their customer base better and tailor their marketing efforts accordingly. This project utilizes the Mall_Customers.csv dataset to perform clustering and visualize the customer segments in 3D.

Dataset:
The dataset used in this project is Mall_Customers.csv, which contains information about customers, including:

-CustomerID: Unique identifier for each customer
-Gender: Gender of the customer
-Age: Age of the customer
-Annual Income (k$): Annual income of the customer in thousands of dollars
-Spending Score (1-100): Spending score assigned based on customer behavior and purchasing data

Project Workflow:

1.Data Loading and Exploration: Load and explore the dataset.
2.Feature Selection: Select the relevant features for clustering (Age, Annual Income (k$), Spending Score (1-100)).
3.Data Normalization: Normalize the selected features for better clustering performance.
4.Optimal Number of Clusters: Use the elbow method to find the optimal number of clusters.
5.K-means Clustering: Apply the K-means algorithm to the normalized data.
6.3D Visualization: Create a 3D scatter plot to visualize the customer clusters.

Installation
To set up the project locally, install the necessary libraries:
- code:
pip install pandas numpy scikit-learn matplotlib seaborn

Visualization:
The project includes a 3D scatter plot to visualize the customer segments. The clusters are color-coded, helping to identify distinct groups based on age, annual income, and spending score.

Contributing:
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

