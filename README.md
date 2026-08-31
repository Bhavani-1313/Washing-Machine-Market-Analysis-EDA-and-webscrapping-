# Washing Machine Market Analysis — EDA

An **Exploratory Data Analysis (EDA)** project focused on understanding the washing machine market through product-level data collected from an e-commerce platform.

The project covers the complete analytical workflow, including **data extraction, data cleaning, feature engineering, exploratory analysis, visualization, business questions, insights, and recommendations**.

## Overview

The objective of this project is to analyze washing machine products based on attributes such as brand, capacity, price, warranty, power rating, RPM, discount, customer rating, and load type.

The project uses Python to transform raw scraped data into a structured dataset and explore patterns and relationships between product characteristics and pricing.

## Project Workflow

```text
Data Extraction
      ↓
Data Collection
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Business Questions
      ↓
Insights & Recommendations
```

## Dataset Attributes

The analysis includes product-level attributes such as:

* Product Name
* Brand
* Capacity
* Price
* Warranty
* Power Rating
* RPM
* Discount
* Customer Rating
* Load Type

## Data Extraction

Product information was collected from Flipkart using Python-based web scraping techniques with:

* `Requests`
* `BeautifulSoup`
* Regular Expressions

The collected data was stored as **Scraped Data.csv**.

## Data Cleaning

The project includes several data preparation steps:

* Extracting brand information from product names
* Checking dataset structure and statistics
* Identifying missing values
* Checking and removing duplicate records
* Cleaning currency symbols and formatting from price values
* Converting numerical columns into appropriate data types

The cleaned dataset was saved as **Cleaned Data.csv**.

## Feature Engineering

Additional categorical features were created to support business analysis:

### Price Category

Products were classified into:

* Budget
* Mid Range
* Premium

### Capacity Category

Products were categorized based on capacity into:

* Small
* Medium
* Large

### Rating Category

Products were grouped based on rating levels:

* Excellent
* Good
* Average

## Exploratory Data Analysis

### Univariate Analysis

The project analyzes individual variables including:

* Brand distribution
* Price category distribution
* Customer rating distribution
* Load-type distribution

### Bivariate Analysis

Relationships analyzed include:

* Capacity vs Price
* Warranty vs Price
* Average Price by Brand
* Average Power Rating by Brand

### Multivariate Analysis

The project explores:

* Capacity vs Price by Brand
* Correlation between numerical variables
* Relationships among Price, Capacity, Power Rating, and Warranty

## Business Questions

The analysis addresses business-oriented questions such as:

* Which brands have the highest number of washing machine models?
* Which price category contains the most products?
* How are washing machine prices distributed?
* How are customer ratings distributed?
* Which brands have the highest average ratings?
* Does higher capacity generally lead to higher prices?
* Does warranty duration relate to product pricing?
* How do different washing machine types compare?

## Key Insights

* The market contains a combination of major brands and brands with smaller product portfolios.
* Budget and Mid-Range products represent significant portions of the analyzed market.
* Most products have customer ratings above 4.0.
* Higher-capacity washing machines generally tend to have higher prices.
* Pricing also varies across different brands.
* Longer warranty periods are associated with higher average product prices in the analyzed dataset.
* Some brands provide higher-capacity products at comparatively competitive prices.

## Business Recommendations

* Expand the Budget and Mid-Range product portfolio.
* Promote highly rated products to improve customer confidence.
* Consider longer warranty periods for selected budget products.
* Maintain sufficient inventory for products with strong market demand.
* Focus on products offering a combination of capacity, ratings, and competitive pricing.

## Technologies & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Requests**
* **BeautifulSoup**
* **Regular Expressions**

## Project Structure

```text
Washing-Machine-Market-Analysis/
│
├── EDA/
│   ├── Washing Machine Market Analysis.ipynb
│   ├── Scraped Data.csv
│   └── Cleaned Data.csv
│
└── README.md
```

## Key Learning Outcomes

This project provided practical experience in:

* Web scraping
* Data collection
* Data cleaning
* Data preprocessing
* Feature engineering
* Univariate analysis
* Bivariate analysis
* Multivariate analysis
* Data visualization
* Correlation analysis
* Business-oriented data interpretation
* Communicating analytical insights
