# Sales Prediction for an online store

Predicting sales is one of the most important business problems for any retail entity. If a business can predict the how much of each item it will sell in each month, it can manage its inventory better. Sales predictions also help in directing the marketing efforts in right direction to increase the chances of sale.

## Objective: 
To forecast item-wise sales for an online retail store

## Dataset used

The dataset has been taken from UCI Machine Learning Repository at: 
https://archive.ics.uci.edu/dataset/502/online+retail+ii


The dataset contains following attributes:

| Attribute Name        | Type           | Description  |
| ------------- |:-------------:| -----:|
| InvoiceNo      | Nominal | A 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'C', it indicates a cancellation |
|StockCode| Nominal| A 5-digit integral number uniquely assigned to each distinct product|
|Description| Nominal|Product (item) name|
|Quantity|Numeric|The quantities of each product (item) per transaction|
|InvoiceDate|Numeric|The day and time when each transaction was generated|
|UnitPrice| Numeric|Product price per unit in sterling|
|CustomerID| Nominal|A 5-digit integral number uniquely assigned to each customer|
|Country|Nominal|Name of the country where each customer resides|

The data is made available by Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK

## Tools used: 

Python, Multiple regression techniques -  Linear Regression
Regularization Models-Ridge, Lasso 
Ensemble Models-Random Forest, Gradient Boost

## Detailed Process
To understand the whole process these links can be followed in order:

[Data Wrangling](https://github.com/manicandone99/Sales_Prediction_Online_Retail_Store/blob/main/A.%20Data%20Aquisition%20%26%20Wrangling.ipynb)

[Exploratory Data Analysis](https://github.com/manicandone99/Sales_Prediction_Online_Retail_Store/blob/main/B.%20EDA.ipynb)

[Statistical Inference](https://github.com/manicandone99/Sales_Prediction_Online_Retail_Store/blob/main/C.%20Inferential%20Statistics.ipynb)

[Machine Learning](https://github.com/manicandone99/Sales_Prediction_Online_Retail_Store/blob/main/D.%20Machine%20Learning.ipynb)

## Project Report
Click [here](https://github.com/manicandone99/Sales_Prediction_Online_Retail_Store/blob/main/Consolidated_Report.pdf) for the full project report.

## Result
The objective of this project was to predict sales for each item in a month. The model we came up with gives us decent results with RMSE of 23 on test data.
