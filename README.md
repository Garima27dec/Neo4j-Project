# Product Recommendation using Graph Database - Neo4j

In this project, we use the graph database Neo4j to produce product recommendations and offers for our customers. Neo4j is a highly scalable, graph database management system, which is a purpose-built database to store and navigate relationships in computing. It stores nodes and relationships (instead of tables or documents) in a graph structure for semantic queries. Hence, making it our chosen database for carrying out product recommendation.


We have the following user stories that articulate how our work will deliver value back to the customer:


•	As a customer, Thomas wants relevant book recommendations whenever he buys a book from the App. 


•	As a customer, Annie would like the App to show personalised recommendations based on what other similar customers are buying. 


•	The customer Nicola would like to see some product discounts /offers based on her recent likes and views on the App.


**Command lines to reproduce execution:** [Product Recommendation & Promotion.txt](https://github.com/Garima27dec/Neo4j-Project/blob/main/Product%20Recommendation%20%26%20Promotion.txt)


**Data Flow:**


![image](https://github.com/Garima27dec/Neo4j-Project/assets/99138272/e593cfde-51df-4043-bcc9-42db067933a2)


*Data Source for User Story 1*: [BooksData.json](https://github.com/Garima27dec/Neo4j-Project/blob/main/BooksData.json)


*Data Source for User Story 2*: [OrdersData.csv](https://github.com/Garima27dec/Neo4j-Project/blob/main/OrdersData.csv), [customers.csv](https://github.com/Garima27dec/Neo4j-Project/blob/main/customers.csv), [products.csv](https://github.com/Garima27dec/Neo4j-Project/blob/main/products.csv)


*Data Source for User Story 3*: https://www.kaggle.com/retailrocket/ecommerce-dataset?select=events.csv
