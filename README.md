Customer Segmentation Using K-means Clustering

This project demonstrates how to perform customer segmentation using the K-means clustering algorithm in Python. The dataset used is the Mall_Customers.csv which contains basic information about customers like their age, annual income, and spending score. This project also includes a 3D visualization of the clustered data to better understand customer segments.

Table of Contents
Introduction
Dataset
Project Steps
Requirements
Usage
Results
Contributing
License
Introduction
Customer segmentation is a key task in marketing that involves dividing a customer base into groups of individuals that are similar in specific ways relevant to marketing, such as age, gender, interests, and spending habits. By understanding these segments, businesses can target their marketing efforts more effectively.

Dataset
The dataset used in this project is Mall_Customers.csv, which contains the following columns:

CustomerID: Unique ID assigned to the customer
Gender: Gender of the customer
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousand dollars
Spending Score (1-100): Spending score assigned to the customer based on their purchasing behavior
The dataset can be found in the data folder or can be downloaded from here.

Project Steps
Data Loading and Exploration: Load the dataset and perform basic data exploration.
Feature Selection: Select relevant features for clustering (Age, Annual Income (k$), Spending Score (1-100)).
Data Normalization: Normalize the selected features.
Optimal Number of Clusters: Use the elbow method to determine the optimal number of clusters.
K-means Clustering: Apply the K-means clustering algorithm to the normalized data.
3D Visualization: Visualize the clusters in a 3D scatter plot.
Requirements
To run this project, you need to have the following libraries installed:

pandas
numpy
scikit-learn
matplotlib
seaborn
You can install these libraries using pip:

sh
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Usage
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/customer-segmentation-kmeans.git
Navigate to the project directory:
sh
Copy code
cd customer-segmentation-kmeans
Run the Jupyter Notebook or the Python script:
sh
Copy code
jupyter notebook customer_segmentation.ipynb
or

sh
Copy code
python customer_segmentation.py
Results
The results of the K-means clustering algorithm are visualized in a 3D scatter plot, showing the customer segments based on age, annual income, and spending score. The clusters are color-coded to indicate different segments.


Contributing
Contributions are welcome! If you have any improvements or suggestions, feel free to create an issue or submit a pull request.
