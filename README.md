# Ebay President Day Analysis 

Web-scrap item information directly from the first 10 pages of "President Day Sale" promotion and perform simple comparison analysis on the items sold

* Extract the item pages and store into separate files based on item id
* Parse item features such as price, shipping, sellerscore, itemsold etc. from html file into dataframe using CSS selector
* Create MySQL database structure and schemes bsed on feature type
* Feature analysis based on quantity sold