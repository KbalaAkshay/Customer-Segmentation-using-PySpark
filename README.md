# Customer-Segmentation-using-PySpark

Customer segmentation is the process of dividing a company’s customer base into distinct groups of individuals that share similar characteristics. These characteristics can be based on demographics, behaviours, purchasing patterns, needs, or preferences. The goal of segmentation is to enable businesses to tailor their marketing strategies, products, and services to better meet the specific needs of each customer group, leading to more effective communication, higher customer satisfaction, and increased business efficiency.

In this project, we use the RFM (Recency, Frequency, Monetary) model for segmentation, followed by clustering using K-means, which helps group customers based on purchasing behaviour.

# Project Overview
The project consists of several steps:

  1) Data extraction and preprocessing.
  
  2) Calculation of RFM scores for each customer.
  
  3) Using K-means clustering to segment customers based on their RFM scores.
  
  4) Analyzing each segment to derive actionable business insights.

By the end of this project, we will have grouped customers into segments such as "High-Value Customers," "At-Risk Customers," and "New Customers."

# Dataset
We use the Online Retail Dataset available from the UCI Machine Learning Repository or from https://archive.ics.uci.edu/dataset/352/online+retail.

Dataset Features:

1) InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction.

2) StockCode: Product code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

3) Description: Product name. Nominal.

4) Quantity: The quantities of each product per transaction. Numeric.

5) InvoiceDate: Invoice date and time. Numeric.

6) UnitPrice: Unit price. Numeric.

7) CustomerID: Customer number. Nominal, uniquely assigned.

8) Country: Country name. Nominal, the name of the country where the customer resides.

