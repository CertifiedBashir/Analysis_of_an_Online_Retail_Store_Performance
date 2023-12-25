# Analysis of an Online Retail Store Performance
> **BY ABDULRAHEEM BASHIR**

## Introduction
This project was inspired by a data gotten from virtual experience programme provided by Tata iQ(Tata Insights and Quants)

**About Data**

The dataset is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Background info and context**

The online retail store wants to review their data and provide insights that would be valuable to the CEO and CMO of the business. The business has been performing well and the management wants to analyse the data so they can strategically plan for next year.

The CEO and CMO want some analysis and visuals that would help answer their questions. Both, the executives are interested in viewing and understanding how they can use the data to make more meaningful decisions on creating an expansion strategy of their retail store.

**Executives Questions:** The executives would like you to answer the following questions:
1. The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.
2. The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.
3. The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.
4. The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.

**Dataset:** The dataset contains one row for each transaction. The dataset(Online Retail Data Set) can be downloaded from kaggle.

**Attribute Information:** The following are the dataset descriptions:
- **InvoiceNo:** Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- **StockCode:** Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- **Description:** Product (item) name. Nominal.
- **Quantity:** The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate:** Invice Date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice:** Unit price. Numeric, Product price per unit in sterling.
- **CustomerID:** Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- **Country:** Country name. Nominal, the name of the country where each customer resides.

I will be providing insights base on the executives questions which they can use to create the expansion strategy. This will help executives understand the trends and the breakdown by different categories so that they have clarity on how the revenue is being generated and what are the main factors affecting the online store.