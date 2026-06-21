
# Olist E-Commerce Performance Analysis

## Project Objective

Analyze Olist's e-commerce performance across revenue, customers, sellers, delivery operations, and geographic regions to identify growth opportunities and operational improvement areas.

## Dataset Overview

This project uses the Brazilian E-Commerce Public Dataset by Olist.

Datasets used:

* Customers Dataset
* Orders Dataset
* Order Items Dataset
* Products Dataset

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Business Questions

1. Which product categories drive the most revenue?
2. How concentrated is revenue among sellers?
3. What purchasing behavior do customers exhibit?
4. How effective are delivery operations?
5. Which states experience the highest delivery delays?

## Key Findings

### Revenue Analysis

23% of product categories (17 out of 74) contribute approximately 80% of total revenue, indicating strong revenue concentration among a relatively small subset of categories.

### Customer Analysis

Repeat purchasing is limited, with 96.9% of customers placing only one order. Only 3.1% of customers made more than one purchase, indicating low customer loyalty and retention.

### Seller Analysis

543 sellers (17.5% of sellers) contribute 80% of total revenue, highlighting a strong dependency on a relatively small group of high-performing sellers.

### Delivery Operations

Delivery performance is generally strong, with 93.2% of orders delivered on or before the estimated delivery date. However, when delays occur, orders arrive an average of 11 days late.

### Geographic Analysis

Delivery performance varies significantly across states, with the highest late-delivery rate being more than four times the lowest. States with longer delivery times also tend to have higher late-delivery rates.

## Business Recommendations

* Prioritize investment in high-performing product categories.
* Improve customer retention through loyalty and repeat-purchase initiatives.
* Reduce revenue concentration risk by supporting smaller sellers while retaining top performers.
* Investigate operational bottlenecks contributing to severe delivery delays.
* Focus logistics improvement efforts on states with consistently high late-delivery rates.


## Key Visualizations

### Revenue by Category

![Revenue by Category](https://github.com/user-attachments/assets/8c11d18d-ace2-47fe-8b4b-5bfd967f2627)

### Seller Revenue Concentration

![Seller Concentration](https://github.com/user-attachments/assets/15065a8e-cc95-4304-82f4-cbc39939ff9c)

### Late Delivery Rate by State

![Late Delivery Rate by State](https://github.com/user-attachments/assets/10009039-6c3c-4120-b9f6-ab7410e8f6c9)

## Repository Structure

```text
olist-ecommerce-performance-analysis/
│
├── notebooks/
│   └── E_Commerece_performance_analysis_.ipynb
│
├── images/
│
└── README.md
```
