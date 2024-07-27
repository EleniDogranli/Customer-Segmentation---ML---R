Customer Segmentation using Machine Learning in R

About This Project
This is my first project in data science, and I am excited to share it with the community. I hope it serves as a useful resource for anyone interested in customer segmentation and unsupervised learning using R. Your feedback and suggestions are highly appreciated!



Overview
Customer segmentation is a critical application of unsupervised learning that helps companies identify distinct customer groups for targeted marketing strategies. This project utilizes K-means clustering to segment customers based on their demographic and behavioral characteristics using the R programming language.

Project Structure
This repository contains the following files and directories:

Mall_Customers.csv: The dataset used for customer segmentation.
Customer_Segmentation.R: The main R script that performs data exploration, visualization, and clustering.
README.md: Project overview and instructions.
presentation/: Directory containing the project presentation slides.
Dataset
The dataset Mall_Customers.csv includes information on mall customers, such as:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature
Project Workflow
The project is divided into several key steps:

1. Data Exploration
Import necessary R packages.
Load and inspect the dataset.
Generate summary statistics and visualize the data distribution.
2. Data Visualization
Customer Gender Visualization: Create bar plots and pie charts to visualize gender distribution.
Age Distribution Visualization: Use histograms and box plots to analyze age distribution.
Annual Income Analysis: Generate histograms and density plots to explore annual income.
Spending Score Analysis: Create box plots and histograms for spending scores.
3. Clustering Using K-means
Determining Optimal Clusters:
Elbow Method: Identify the optimal number of clusters by plotting the total intra-cluster sum of squares.
Average Silhouette Method: Compute average silhouette width for different cluster sizes.
Gap Statistic Method: Estimate the optimal number of clusters using the gap statistic method.
K-means Clustering: Implement K-means clustering and analyze the results.
Cluster Visualization: Use Principal Component Analysis (PCA) to visualize the clustering results.
