# E-Commerce Customer Purchase Prediction using Machine Learning

## Project Overview
This project focuses on predicting whether a customer will make a purchase on an e-commerce website based on their browsing behavior and shopping activity.

The objective is to build a **classification model** that can accurately predict the target variable **purchase** using customer activity features.

The project follows a complete **Machine Learning workflow**, including:

- Problem understanding
- Data loading
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Handling null values
- Duplicate handling
- Outlier detection
- Univariate and bivariate analysis
- Encoding categorical data
- Model building using Random Forest
- Performance evaluation

---

## Problem Statement
E-commerce platforms want to predict whether a user visiting the website is likely to make a purchase.

This helps businesses in:

- personalized recommendations
- discount popups
- targeted marketing
- customer conversion optimization

This is a **Supervised Machine Learning Classification Problem**

### Target Variable
`purchase`

- `1` → Customer made a purchase
- `0` → Customer did not make a purchase

---

## Dataset Description
A **synthetic dataset of 500 rows** was created with realistic business relationships between variables.

### Features Used

| Feature Name | Description |
|---|---|
| time_spent_minutes | Total time spent on website |
| pages_viewed | Number of pages viewed |
| products_viewed | Number of products viewed |
| items_added_to_cart | Items added to cart |
| device_type | Mobile / Desktop / Tablet |
| traffic_source | Google / Instagram / Ads / Direct |
| is_returning_customer | Existing customer or not |
| discount_used | Whether discount was applied |
| previous_purchases | Number of previous orders |
| average_cart_value | Average cart value |
| purchase | Target variable |

---

## Libraries Used

```python
pandas
numpy
matplotlib
seaborn
sklearn
