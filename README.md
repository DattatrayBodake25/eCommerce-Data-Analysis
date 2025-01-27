# Data Science Assignment: eCommerce

## Overview
This project is focused on performing a detailed analysis of an eCommerce dataset and developing machine learning models to generate business insights and actionable recommendations. The dataset consists of three files: **Customers.csv**, **Products.csv**, and **Transactions.csv**. The task involves:

- Performing Exploratory Data Analysis (EDA).
- Building a Lookalike Model for customer recommendations.
- Implementing customer segmentation using clustering techniques.

## Files Description

### 1. **Customers.csv**
- **CustomerID**: Unique identifier for each customer.
- **CustomerName**: Name of the customer.
- **Region**: Continent where the customer resides.
- **SignupDate**: Date when the customer signed up.

### 2. **Products.csv**
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Product price in USD.

### 3. **Transactions.csv**
- **TransactionID**: Unique identifier for each transaction.
- **CustomerID**: ID of the customer who made the transaction.
- **ProductID**: ID of the product sold.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity of the product purchased.
- **TotalValue**: Total value of the transaction.
- **Price**: Price of the product sold.

## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Perform EDA on the provided dataset.
- Derive at least 5 business insights from the EDA.
- Present insights in short point-wise sentences (maximum 100 words per insight).

#### Deliverables:
- Jupyter Notebook/Python script with EDA code.
- PDF report containing business insights (maximum 500 words).

### Task 2: Lookalike Model
Build a Lookalike Model that recommends 3 similar customers based on their profile and transaction history. The model should:
- Use both customer and product information.
- Assign a similarity score to each recommended customer.

#### Deliverables:
- A CSV file ("Lookalike.csv") containing the top 3 lookalikes and their similarity scores for the first 20 customers (CustomerID: C0001 - C0020).
- Jupyter Notebook/Python script explaining the model development.

### Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques. Use both profile information (from **Customers.csv**) and transaction information (from **Transactions.csv**).
- Choose any clustering algorithm and specify the number of clusters (between 2 and 10).
- Calculate clustering metrics, including the DB Index.
- Visualize the clusters using relevant plots.

#### Deliverables:
- A report containing the clustering results:
  - Number of clusters formed.
  - DB Index value.
  - Other relevant clustering metrics.
- Jupyter Notebook/Python script with clustering code.

## Submission Instructions

1. **GitHub Repository Link**
   - Upload all the PDF and code files in a **public** GitHub repository.
   
2. **File Naming Convention**
   - Use the following naming convention for all files:
     - `FirstName_LastName_EDA.pdf`
     - `FirstName_LastName_EDA.ipynb`
     - `FirstName_LastName_Lookalike.csv`
     - `FirstName_LastName_Lookalike.ipynb`
     - `FirstName_LastName_Clustering.pdf`
     - `FirstName_LastName_Clustering.ipynb`

## Evaluation Process

Submissions will be evaluated based on the following criteria:

- **Exploratory Data Analysis** (25%)
- **Business Insights** (15%)
- **Lookalike Model** (30%)
- **Customer Segmentation** (30%)

Given the large number of submissions, the evaluation will be automated as much as possible. Ensure your file formats and naming conventions are accurate to avoid disqualification.

## Final Note

This comprehensive assignment tests critical thinking and the application of data science concepts. Focus on creating clean, efficient code and providing actionable insights that can guide business strategy.

Good luck!
