OList is one such e-commerce company that has faced some losses recently and they want to manage their inventory very well so as to reduce any unnecessary costs that they might be bearing. Our main objective for this project are as follows:

 Identify top product contributing to revenue .
 Analyze purchase behavior of individual customer using market basket analysis and Pareto Analysis.
Determine which items are most likely to purchased individually or in combination with other products.
 Identify the product categories which they can get rid of without significantly impacting business.	

Appendix - Data Sources
Here is a snapshot of our data dictionary:
Order details such as order id, order status, order purchased timestamp, etc.
Order Items detail such as order item id, seller id, price, shipping charges, etc.
Customer details such as customer id, customer zip code, customer city, customer state, etc.
Payment details such as payment type, payment value, etc.
Product details such as product id, product category name, product dimensions, etc.

The following data sources were used:
OList retail dataset containing order-related information.
The data consisted for the year 2016 to 2018.

A thorough analysis of the OList Retail Dataset was conducted. The process included:
The dataset was cleaned and transformed using the python libraries of Pandas and Numpy in the Jupyter Notebook.
The missing values for the various columns were replaced with the best values.
The redundant and duplicate records were discarded and only first occurrence is kept.
Exploratory data analysis was done using the python libraries of Matplotlib and Seaborn in the Jupyter Notebook.
A new dataset consisting of order id and product category name was created for Market Basket Analysis.
Various visualizations and Market Basket Analysis was conducted in Tableau.

Appendix - Data Assumptions
Only the cases having order status as ‘delivered’ are considered.
We assumed that the data provided was achieving the desired revenue.
We assumed that the company does not want to expand to new warehouses.
The company’s strategies are decided considering there is constant growth in sales.

Recommendations
The company should focus on the categories which generate more than 80% of the revenue by always keeping them in stock.
The company should target customers who are more likely to buy toys to boost sales as the category toys is the most ordered category.
Offer promo-codes or discounts on the frequently ordered category associations to encourage cross selling among the products.
The company can reduce some of the sub categories which have very low sales.


