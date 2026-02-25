📊 Retail Customer Segmentation using K-Means Clustering
📌 Project Overview

This project demonstrates customer segmentation in the retail sector using the K-Means clustering algorithm. The objective is to group customers based on purchasing behavior and demographic characteristics to enable targeted marketing strategies and business decision-making.

The project includes:

Implementation of K-Means from scratch

Clustering using Scikit-Learn

Optimal cluster selection using:

Elbow Method

Silhouette Score Analysis

3D cluster visualization

Business interpretation of segments

🗂 Dataset Description

A synthetic retail dataset of 500 customers was generated with the following features:

Age

Gender

Profession

Annual Income

Spending Score

Loyalty Points

Purchase Frequency

These features simulate real-world retail customer behavior.

⚙️ Methodology
1️⃣ K-Means from Scratch

Random centroid initialization

Euclidean distance calculation

Cluster assignment

Centroid update

Iterative optimization

2️⃣ Data Preprocessing

Feature scaling using StandardScaler

3️⃣ Optimal Cluster Selection

Elbow Method (WCSS)

Silhouette Score analysis

4️⃣ Final Model

Best value of k selected using silhouette score

Model training using Scikit-Learn KMeans

Cluster visualization

📈 Visualizations

Elbow Curve for optimal k detection

Silhouette Score curve

3D cluster visualization (Income, Spending Score, Loyalty Points)

🧠 Business Use Case (Retail Industry)

This segmentation model can help retailers:

Identify high-value customers

Design loyalty programs

Personalize marketing campaigns

Improve customer retention

Optimize promotional strategies

🛠 Technologies Used

Python

NumPy

Pandas

Matplotlib

Scikit-Learn
