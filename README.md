Overview

This project performs customer segmentation based on their spending patterns and demographics using the K-Means clustering algorithm.
The goal is to help mall management understand different customer groups so they can implement targeted marketing strategies and improve customer experience.

 Objective

To analyze mall customer data and identify distinct groups (clusters) of customers based on:

Age

Annual Income

Spending Score

These insights can assist in marketing strategy design, loyalty programs, and customer engagement decisions.

 Technologies Used

Python 

Pandas – Data manipulation

NumPy – Numerical computations

Matplotlib & Seaborn – Data visualization

Scikit-learn (sklearn) – Machine learning (KMeans)

 Dataset

The dataset used is typically known as Mall_Customers.csv, which contains the following columns:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

 Steps Involved

Data Loading & Exploration – Import dataset and explore structure.

Data Visualization – Analyze distribution of income, spending, and age.

Feature Selection – Select features relevant for clustering (Annual Income, Spending Score).

Finding Optimal Clusters – Use the Elbow Method to determine the best number of clusters.

Model Training – Apply K-Means clustering using the chosen number of clusters.

Visualization of Clusters – Plot clusters to visualize different customer groups.

Insights Generation – Interpret results to understand customer segments (e.g., high spenders, low income–low spending, etc.).

 Example Insights

Customers with high income and high spending may be potential premium members.

Low income and low spending customers may require special offers to engage more.

Middle-income segments could represent regular buyers.
