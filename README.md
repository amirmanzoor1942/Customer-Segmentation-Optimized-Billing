**Customer Segmentation for Optimizing Bill Recovery at ABC-Electric**

**Project Overview**

This project aims to enhance recovery efficiency at ABC-Electric by segmenting customers based on their electricity usage and payment behavior. Using K-Means clustering and Principal Component Analysis (PCA), we categorize customers into different groups, allowing for targeted strategies to improve payment recovery.

**Features**

•	Data Preprocessing: Cleans missing values and standardizes numerical features.

•	Clustering Using K-Means: Identifies customer segments based on payment and electricity usage data.

•	Dimensionality Reduction Using PCA: Visualizes clusters in a 2D space.

•	Optimal Cluster Selection: Uses the Elbow Method to determine the best number of clusters.

•	Cluster Insights: Analyzes customer groups to improve recovery strategies.

**Technologies Used**

•	Python

•	Pandas

•	NumPy

•	Matplotlib & Seaborn (for visualization)

•	Scikit-learn (for clustering and PCA)

**Dataset**

The dataset contains the following features:

•	Customer_ID: Unique identifier for customers

•	Monthly_Bill: Monthly electricity bill

•	Outstanding_Balance: Unpaid balance amount

•	Payment_Delay_Days: Number of days a customer delayed payment

•	Electricity_Usage_kWh: Energy consumption in kilowatt-hours

**How It Works**

1.	Load the dataset and preprocess missing values.

2.	Standardize the data for better clustering.

3.	Apply K-Means clustering to group customers into segments.

4.	Use PCA to reduce dimensionality and visualize the clusters.

5.	Analyze customer groups to generate insights for optimized recovery strategies.

**Future Enhancements**

•	Implementing Deep Learning models for better segmentation.

•	Adding time-series analysis to track customer payment patterns over time.

•	Integrating with real-time dashboards for visualization.

**License**

This project is licensed under the MIT License.

**Author**

Developed by Dr. Amir Manzoor
