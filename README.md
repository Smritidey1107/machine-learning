Game Hunt: Student Friendship Group Clustering
This project analyzes the "snu_friendship.csv" dataset to identify and cluster students into "friendship groups" based on shared hobbies and club interests. The analysis follows a structured plan to preprocess the data, apply clustering techniques, and derive meaningful insights.

Project Goal
The primary objective is to analyze the snu_friendship.csv dataset and use clustering to group students with similar hobbies and club interests.

Methodology
1. Data Loading and Inspection
The snu_friendship.csv file is loaded into a pandas DataFrame. Initial inspection is performed to understand the data structure and types of the columns.

2. Data Preprocessing
Categorical features, such as hobbies and club affiliations, are converted into a numerical format using one-hot encoding, as this is a requirement for most clustering algorithms. The project also handles any missing or non-numerical values to ensure data integrity.

3. Clustering
K-Means clustering is applied to the preprocessed data to create distinct student groups. The optimal number of clusters is determined by analyzing evaluation metrics like the silhouette score and the Davies-Bouldin index. The chosen number of clusters is between 2 and 10.

4. Visualization and Insights
Principal Component Analysis (PCA) is used to reduce the data to two dimensions for easy visualization. This allows for a 2D plot of the clusters, which helps to visually assess the separation between groups. The project also provides a breakdown of each cluster by calculating descriptive statistics for numerical features and identifying the most frequent values for categorical features.

File Contents
Game hunt.ipynb: The Jupyter Notebook containing the code and analysis.

snu_friendship.csv: The dataset used in the analysis.

Key Outcomes
The project successfully identified student clusters based on shared interests.

The final clustering achieved a silhouette score of approximately 0.499 and a Davies-Bouldin index of about 0.316.

The insights derived from the cluster analysis can be used to organize social activities, personalize communications, and facilitate connections among students.
