## Instacart_Consumer_trends_Analysis_Prediction

The data was collected from [kaggle](https://www.kaggle.com/c/instacart-market-basket-analysis) consists of metadata for over 3 million Instacart orders from more than 200,000 users distributed over five tables which are department, aisle, product, prior_orders, transactions. <br>
Using exploratory data analysis we aim to observe consumer buying patterns on department, aisles and products level; effect of day of week and hour of day on number of orders; best selling products throughout orders ; reordering proportions and patterns to know products getting reordered and interval of reorders; number of times each product getting reordered; average number of products getting added to shopping cart. In addition, we seek to identify item sets which are usually bought together and generate association rules based on different parameters such as support, threshold and lift. 

### Key takeaways and results
1. There are 13,84,617 products in the order_products_train file and 3,24,34,489 products in the order_products_prior file. Both files have 4 feature columns:
The ID of the order (order_id)
The ID of the product (product_id)
The ordering of that product in the order (add_to_cart_order)
Whether that product was reordered (reordered).
2. Overall, there are 33,46,083 unique orders for 49,685 unique products.

3. Customers usually order around 5 or 6 products in an order. 
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta10.png" width="400" height="150">
4. Mostly customers buy 3 to 7 items in an order.  
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta1.png" width="400" height="150">
5. We see that products are either reordered after a month or after 7 days.
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta2.png" width="400" height="150">
6. Most orders are placed between 10 am to 4pm. 
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta3.png" width="400" height="150">
7. Clearly most orders are made on Saturday followed by Sunday.
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta4.png" width="400" height="150">
8. Top five popular item happens to be :   
Banana	(491291),			
Bag of Organic Bananas	(394930	),		
Organic Strawberries	(275577	),		
Organic Baby Spinach	(251705)			
Organic Hass Avocado	(220877)   
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta6.png" width="400" height="150">
9. M0st reordered product is Banana followed by Bag of bananas
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta5.png" width="400" height="150">
10. Frequent Itemsets
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta7.png" width="400" height="150">
11. Scatter plot of 38 Rules
<img src="https://github.com/sharmasapna/Instacart_Consumer_trends_Analysis_Prediction/blob/main/images/insta9.png" width="400" height="150">

