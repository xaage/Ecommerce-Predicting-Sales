# E-commerce transactions: data analysis, RFM and predicting sales

## Description
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

The project is an independent approach to understand customer insights using a large dataset from UCI Machine Learning Repository. 

Online Retail Data Set: https://archive.ics.uci.edu/ml/datasets/online%2Bretail#

## The columns consist of:<br>

* *InvoiceNo*: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* *StockCode*: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* *Description*: Product (item) name. Nominal.
* *Quantity*: The quantities of each product (item) per transaction. Numeric.
* *InvoiceDate*: Invoice Date and time. Numeric, the day and time when each transaction was generated.
* *UnitPrice*: Unit price. Numeric, Product price per unit in sterling.
* *CustomerID*: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* *Country*: Country name. Nominal, the name of the country where each customer resides.

## Approach
To help the retailer better understand its customers, the following procedures were performed:
1. Exploratory Analysis
2. Time series
3. RFM (Recency, Frequency, Monetary)
4. Predicting sales
