# E-Commerce Customer Segmentation & Recommendation Analysis

## Project Overview

The **E-Commerce Customer Segmentation & Recommendation Analysis** project focuses on understanding customer purchasing behaviour and identifying different customer groups using Machine Learning techniques.

The project applies **RFM (Recency, Frequency, Monetary) Analysis**, **K-Means Clustering**, and a **Product Recommendation System** to analyse customer patterns and generate personalised product recommendations.

A synthetic e-commerce dataset is generated using Python to demonstrate the complete data analysis and machine learning workflow.

## Objectives

- Analyse customer purchasing behaviour.
- Perform data cleaning and preprocessing.
- Calculate Recency, Frequency, and Monetary values.
- Segment customers using K-Means Clustering.
- Visualise customer groups using PCA.
- Recommend similar products based on purchase patterns.
- Generate useful insights to support business decisions.

## Technologies Used

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Algorithms:** K-Means Clustering, PCA, Nearest Neighbors

## Dataset Information

This project uses a **synthetically generated e-commerce dataset** created within the notebook.

The dataset contains sample information such as:

- Customer ID
- Invoice Number
- Invoice Date
- Product ID
- Product Name
- Quantity
- Unit Price
- Total Purchase Amount

The synthetic dataset allows the complete workflow to run without manually downloading an external dataset.

**Note:** The generated data is intended for project demonstration and does not represent actual customer transactions.

## Project Workflow

### 1. Data Generation
Generate sample e-commerce transaction data using Python.

### 2. Data Preprocessing
- Handle missing values.
- Remove duplicate records.
- Remove invalid quantities and prices.
- Calculate total purchase amounts.
- Convert date columns into the appropriate format.

### 3. Exploratory Data Analysis (EDA)
- Analyse sales distribution.
- Identify popular products.
- Examine customer purchasing patterns.
- Visualise transaction trends.

### 4. RFM Analysis

Calculate three important customer metrics:

- **Recency:** Number of days since the customer's last purchase.
- **Frequency:** Total number of purchases made by the customer.
- **Monetary:** Total amount spent by the customer.

### 5. Customer Segmentation

Apply the **K-Means Clustering algorithm** to group customers based on their RFM values.

The project identifies four customer clusters for analysis.

### 6. Data Visualisation

Use PCA (Principal Component Analysis) to reduce the customer data to two dimensions and visualise the clusters.

### 7. Product Recommendation System

Use the **Nearest Neighbors algorithm** with cosine similarity to identify and recommend products with similar purchase patterns.

### 8. Export Results

Save the generated analysis results as CSV files for further use.

## Machine Learning Techniques

| Technique | Purpose |
|---|---|
| RFM Analysis | Understand customer purchasing behaviour |
| K-Means Clustering | Group customers into segments |
| PCA | Visualise customer clusters |
| Nearest Neighbors | Recommend similar products |

## Project Outputs

The notebook generates the following output files inside the `ecommerce_project_outputs` folder:

- `cleaned_transactions.csv` – Cleaned transaction dataset.
- `customer_rfm_segments.csv` – Customer RFM metrics and cluster assignments.
- `product_recommendations.csv` – Product recommendation results.
- `customer_cluster_summary.csv` – Summary of customer segments.

It also generates visualisations for sales analysis, customer segmentation, and product recommendations.

## How to Run the Project

1. Clone or download this repository.
2. Open Jupyter Notebook or JupyterLab.
3. Create a new Python notebook.
4. Copy the project code into a notebook cell.
5. Run the cell.
6. View the generated charts and analysis results.
7. Check the `ecommerce_project_outputs` folder for exported CSV files.

## Applications

- Customer relationship management.
- Targeted marketing campaigns.
- Customer retention strategies.
- Personalised product recommendations.
- E-commerce business intelligence.

## Future Enhancements

- Use a real-world e-commerce transaction dataset.
- Develop a web-based customer segmentation dashboard.
- Improve recommendations using collaborative filtering.
- Apply additional clustering algorithms.
- Deploy the recommendation system as a web application.

## Conclusion

This project demonstrates how Data Analytics and Machine Learning can be used to understand e-commerce customer behaviour, segment customers into meaningful groups, and generate product recommendations.

It provides practical exposure to data preprocessing, exploratory data analysis, feature engineering, unsupervised machine learning, data visualisation, and recommendation techniques.

## Author

**Gayatri Gangane**

MCA Student | Aspiring AI/ML Engineer

**Skills:** Python | Data Analytics | Machine Learning | SQL | Data Visualisation
