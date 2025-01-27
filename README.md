# Data Science Assignment: eCommerce Transactions Dataset

## Overview
This assignment focuses on analyzing an eCommerce Transactions dataset provided with three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The goal is to perform exploratory data analysis (EDA), build predictive models, and derive actionable insights to help improve the business strategy.

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Description**: 
  - Perform EDA on the provided dataset.
  - Derive at least 5 actionable business insights based on the analysis.
  - Provide a PDF report summarizing the insights and a Jupyter notebook with the code.
  
- **Deliverables**:
  - `FirstName_LastName_EDA.pdf`: PDF report with business insights.
  - `FirstName_LastName_EDA.ipynb`: Jupyter notebook containing the EDA code.

### Task 2: Lookalike Model
- **Description**: 
  - Build a Lookalike Model that recommends 3 similar customers based on their profiles and transaction history.
  - Use both customer and product data to calculate a similarity score for each recommended customer.
  
- **Deliverables**:
  - `FirstName_LastName_Lookalike.csv`: CSV file containing the recommended lookalikes for the first 20 customers (CustomerID: C0001 - C0020).
  - `FirstName_LastName_Lookalike.ipynb`: Jupyter notebook with code explaining the development of the Lookalike model.

### Task 3: Customer Segmentation / Clustering
- **Description**: 
  - Perform customer segmentation using clustering techniques.
  - Use both customer profile data and transaction data to segment customers.
  - Calculate clustering metrics (including DB Index) and visualize the clusters.
  
- **Deliverables**:
  - `FirstName_LastName_Clustering.pdf`: PDF report summarizing clustering results and metrics.
  - `FirstName_LastName_Clustering.ipynb`: Jupyter notebook with code explaining the clustering approach.

## File Structure
- `FirstName_LastName_EDA.pdf`: Business insights based on EDA.
- `FirstName_LastName_EDA.ipynb`: Code for EDA analysis.
- `FirstName_LastName_Lookalike.csv`: Lookalike model recommendations and similarity scores for the first 20 customers.
- `FirstName_LastName_Lookalike.ipynb`: Code for the Lookalike model.
- `FirstName_LastName_Clustering.pdf`: Clustering results and metrics.
- `FirstName_LastName_Clustering.ipynb`: Code for customer segmentation using clustering.

## Requirements
To run the notebooks, you need the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- scipy

You can install them using the following:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
