# Data Science Assignment: eCommerce Transactions Dataset

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Files](#data-files)
- [Tasks](#tasks)
- [Usage](#usage)
- [Files Structure](#files-structure)
- [Requirements](#requirements)

## Project Overview
Provided with an eCommerce Transactions dataset consisting of three files: Customers.csv, Products.csv, and Transactions.csv. Performed
exploratory data analysis (EDA), build predictive models, and derive actionable insights. 
## Data Files

* Customers.csv (CustomerID, CustomerName, Region, SignupDate)[Download here](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)
* Products.csv (ProductID, ProductName, Category, Price)[Download here](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)
* Transactions.csv (TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, Price)[Download here](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)

## Tasks
### 1. Exploratory Data Analysis

Comprehensive analysis of customer behavior, transactions, and product preferences
Generated 5 key business insights
Deliverables: Jupyter notebook with analysis code and PDF report

### 2. Lookalike Model

Identifies 3 similar customers based on profile and transaction history
Features: Customer profile, purchase patterns, region matching
Deliverables:

Lookalike.csv with customer mappings
Python script for model implementation
Top 3 lookalikes for customers C0001-C0020



### 3. Customer Segmentation

K-means clustering (2-10 clusters)
Evaluation using Davies-Bouldin Index
Visualization of cluster distributions
Deliverables:

Clustering report with metrics
Jupyter notebook with clustering code



## Usage
#Install requirements
* pip install pandas numpy sklearn matplotlib seaborn

#Run analyses
* jupyter notebook
# Files Structure
```bash
project/
├── data/
│   ├── Customers.csv
│   ├── Products.csv
│   └── Transactions.csv
├── notebooks/
│   ├── 1_EDA.ipynb
│   ├── 2_Lookalike_Model.ipynb
│   └── 3_Clustering.ipynb
└── output/
    ├── business_insights.pdf
    ├── Lookalike.csv
    └── clustering_report.md
```
# Requirements

* Python 3.8+
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
