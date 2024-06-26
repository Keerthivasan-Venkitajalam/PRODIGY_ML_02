# Customer Segmentation with K-Means Clustering 🛒

## Overview

This project aims to segment retail store customers into distinct groups based on their purchase history using the K-means clustering algorithm. By identifying these customer segments, the project helps in understanding customer behavior, which can be utilized for targeted marketing and improving customer satisfaction.

![Customer Segmentation](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Cluster2d.svg/640px-Cluster2d.svg.png)

---

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)

---

## Project Description

The project involves:

- **Data Preprocessing:** Cleaning and transforming the dataset to prepare it for clustering.
- **Clustering:** Applying K-means clustering to group customers based on their purchase history.
- **Visualization:** Plotting the clusters to analyze and interpret customer segments.
- **Insights:** Providing actionable insights for marketing strategies.

---

## Dataset

The dataset contains customer purchase history, which includes details like:

- **Customer ID:** Unique identifier for each customer.
- **Purchase Amount:** Total purchase amount.
- **Purchase Frequency:** Number of purchases made by the customer.
- **Last Purchase Date:** The date of the last purchase made.

Make sure the dataset is in CSV format and placed in the root directory of this repository.

---

## Methodology

### 1. **Data Preprocessing**
   - Handling missing values.
   - Normalizing purchase amounts.
   - Converting categorical data to numerical format.

### 2. **K-means Clustering**
   - Choosing the number of clusters using the Elbow Method.
   - Applying K-means clustering to segment customers.
   - Analyzing cluster centroids to understand customer profiles.

### 3. **Visualization**
   - Scatter plots to visualize customer segments.
   - Heatmaps for feature importance in clusters.

---

## Results

The clustering reveals distinct customer segments such as:

- **High-Spending Regulars:** Customers who frequently make high-value purchases.
- **Occasional Shoppers:** Customers who purchase occasionally but spend moderately.
- **New Customers:** Recent customers with few purchases.

These insights help tailor marketing strategies to different customer segments, enhancing customer engagement and retention.

---
