# RFM-Model-Clustering-Analysis
![Project Logo](/clusters.png)
## INTRODUCTION
This model evaluates customer behavior based on three key metrics: __recency__, which assesses how recently a customer has made a purchase; the total monetary value of a customer’s transactions. RFM facilitates the identification of buyer characteristics that influence response.
### __Dataset Information__
This peoject utilized  UK-based and registered, non-store online retail
dataset encompassing two-year transactions recorded on 
01/12/2009 and 09/12/2011,contained 525461 entries across
8 attributes as seen on __Table I__.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers. 

##### __Table I__.
|__ATTRIBUTE__|__DESCRIPTION__|
|----------|----------|
|__Invoice__| Invoice number(Nominal): A 6-digit integral number distinctly identifying each transaction. If this code starts with the letter '__c__', it indicates a __cancellation__|
|__StockCode__| Product (item) code (Nominal): A 5-digit integral number A distinct identity for every product |
|__Description__|An overview of the product(Nominal)|
|__Quantity__| The quantities of each product (item) per transaction(Numeric)|
|__InvoiceDate__| Invice date and time (Numeric): The date of the transaction| 
|__Price__ | Unit price (Numeric): Product price per unit in sterling (Â£)|
|__CustomerID__| Customer number (Nominal): A 5-digit integral number unique identifier to each customer|
|__Country__| Country name (Nominal): Customer’s location|


### DATA ANALYSIS
Upon analysis, the dataset exhibited missing values for 'Customer ID' & 'Description' which needed to be removed.Data with null Customer ID, transactions with negative values, and lines without customer numbers are impacted by this step.

* #### Data Pre-processing
* #### Create the RFM Table and calculate the RMF quantiles
* #### 







