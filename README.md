# E-Commerce-Customers-Project

A linear regression model to predict customer yearly spending based on their online behavior and membership data.

## 📋 Project Overview

This project analyzes customer data from an ecommerce company and builds a predictive model to forecast yearly spending based on customer behavior patterns. The model helps identify which factors most influence customer spending.

## 🎯 Business Problem

Ecommerce companies want to understand what drives customer spending to optimize their platforms and marketing strategies. This project answers:
- What factors most influence customer yearly spending?
- Should the company focus more on mobile app or website development?
- How does membership length affect customer loyalty and spending?

## 📊 Dataset Description

The dataset contains customer information with the following columns:

- **Email**: Customer email address
- **Address**: Customer physical address
- **Avatar**: Customer avatar color/type
- **Avg. Session Length**: Average session of in-store style advice sessions (minutes)
- **Time on App**: Average time spent on App in minutes
- **Time on Website**: Average time spent on Website in minutes
- **Length of Membership**: How many years the customer has been a member
- **Yearly Amount Spent**: Target variable - total amount spent yearly ($)

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
