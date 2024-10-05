# Customer Segmentation Using K-Means

This project aims to segment customers from a shopping mall based on their annual income and spending habits, using the K-Means clustering algorithm. By understanding different customer groups, the mall can create targeted marketing strategies to improve customer satisfaction and increase revenue.

## Purpose

The goal of this project is to use machine learning techniques to discover meaningful customer segments that can provide insights into consumer behavior. This helps in making data-driven business decisions that optimize marketing strategies, product placement, and customer engagement.

## Business Impact

With effective customer segmentation, the mall can:
- Tailor marketing campaigns to different customer groups.
- Identify high-value customers and focus efforts on customer retention.
- Create personalized offers and discounts, improving customer satisfaction.

## Project Overview

The K-Means algorithm is applied to a dataset containing customer information. Although the dataset includes several features (such as age and gender), only **Annual Income** and **Spending Score** were used for the segmentation in this exercise.

### Features used:
- **Annual Income**: The customer's yearly income.
- **Spending Score**: A score assigned to the customer based on their spending habits (1-100).

### Features in the dataset:
- **Customer ID**: A unique identifier for each customer.
- **Gender**: Customer's gender.
- **Age**: Customer's age.
- **Annual Income**: The customer's yearly income.
- **Spending Score**: The amount the customer spends annually in the shopping mall (on a scale from 1 to 100).

## Input Form for Classification

A small form is included where users can input **Annual Income** and **Spending Score** to predict which customer segment they belong to.

## Google Colab

If you prefer to run the project in the cloud, you can execute it on Google Colab. Simply click the link below to open the notebook and run it:
[Customer Segmentation on Google Colab](https://colab.research.google.com/drive/1t4vF09UVlPeLbSPV8fn99IJ0fcMpUVJ8?usp=sharing)

## Results

The K-Means algorithm successfully segmented the customers into different clusters, providing valuable insights into customer behaviors based on their income and spending patterns. This information can be used to optimize the business's marketing and customer relations strategies.

## Future Improvements

- Incorporating additional features (e.g., age, gender) to improve the clustering model.
- Exploring other clustering algorithms like DBSCAN or hierarchical clustering for comparison.
- Analyzing the impact of cluster-specific marketing campaigns on customer retention.

## Credits

This project was completed as part of the **Machine Learning A-Z™: Hands-On Python & R In Data Science** course by **Kirill Eremenko** and **Hadelin de Ponteves** on Udemy.
