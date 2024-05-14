# TASK
Context
The provided dataset has information on 100k orders from 2016 to 2018 from a large ecommerce market place. Its features allow you to view an order from multiple dimensions : 
order status, product attributes, price, etc. The merchants are able to sell their products through 
the marketplace and ship them directly to the customers.

#Description of datasets
1. customers_dataset.csv : This dataset groups the customers information (customer 
id and geolocation information). There are duplicate customer_unique_id, because 
the dataset is per order. Where client_id is the key to the order dataset. Each order 
has a unique client_id.
2. orders_dataset.csv : This dataset groups the order information (customer, order 
status, tracking in time), identified by a unique order_id and attached to a customer 
by the customer_id.
3. order_items_dataset.csv : This dataset groups order information related to each 
product purchased (product id, quantity = order_item_id, price of product, etc.)
4. products_dataset.csv : This dataset gathers the product categories as well as 
various characteristics of dimensions and weight of each product.
5. product_category_name.csv : Translated product category in English

#dataset can be found in the folder, two ipynb files are the code 
