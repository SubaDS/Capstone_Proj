Capstone  Project


SHOE BRAND CAPSTONE 

This capstone is divided into 4 Phase(weekly) duration. In this document the entire details of 4 Phase(weekly) duration is given. 

Phase 1                                                                                                                                            

 Web scrapping the below given six URL :

 

https://www.nike.com

https://www.adidas.com

https://us.puma.com/us/en

https://www.skechers.com

https://www.columbia.com/


https://www.woodlandworldwide.com/




Phase 2                                 

                       

Make the table in  csv format  (3 csv files)  

 

Table1.csv  

 ShoeName ,Category(Men/Women), no.of colors,price  

 

Table2.csv

 count of sizes, colors 1, color 2, color3 ,color4, color5, Style code/product code  

 

Table3.csv 

 reviews, Size, comfort, durability /quality/performance(quantification), star rating, 

 



 Write the SQL queries :

  Table 1           

1 Write a query  to retrieve all shoe names and their corresponding prices for men's shoes:

2 Write a query to retrieve the number of different colors available for each category.

3 Write a query to find the most expensive men's shoe.

4 Write a query to find the cheapest women's shoe in a specific color (e.g., 'Black ').

5 Write a query to retrieve all shoe names and their corresponding prices for men's shoes.



Table 2

1 Write a query that retrieves the count of sizes for all styles.

2  Write a query to list all styles with their associated colors.

3 Write a to find styles that have more than one color.

4  Write a query to find the count of sizes available for each color for a specific style code.


5  Write a query to find styles that have a specific color.



Table 3

1 Write a query calculates the average comfort rating for a specific product based on its reviews.

2  Write a query to retrieve products with high star ratings (e.g., 4 stars or above)

3 Write a query that counts the number of reviews for each product.

4  Write a To retrieve products that have a quantified durability/quality/performance rating above a certain threshold (e.g., above 7).


5 Write a query that  calculates the average comfort rating for each size.




Join SQL Queries  using all 3 tables:

 1 Write a query finds the top-rated men's shoes along with their sizes from "Table1" and "Table3."


2  Write a  query calculates the average comfort rating for each category from "Table1" and "Table3."

3  Write a  query identifies products with a durability/quality/performance rating higher than the average from "Table1" and "Table3."


 4    Write a  subquery finds products with comfort ratings above the average comfort rating using "Table1" and "Table3."


 5 Write a  query joins Table 1  and Table 2  using the "Style code/Product code" column, allowing you to retrieve shoe information along with product details.


 

 6 Write a  query that  identifies products with a star rating above the average star rating for their respective size.


  

7  Write  a  query finds products with the highest comfort rating in each category.






Phase  3                                                                                

 

Now make only 1 dataframe of 3 csv file using concat/merge /join operation of pandas and start doing EDA .


Do the complete EDA in details to explore the insights of data and write the detailed observations of each analysis .







 Phase 4                                                                            

Write the complete Machine learning code to make predictions of price and star rating .Use appropriate models on their label basis. Remember you need to make 2 different predictions: price  and star rating  .

Apply all the best techniques of scaling ,hyperparameter tuning , avoid underfitting or overfitting (bias/variance)

At the end save the best model and convey on which basis you have chosen that model. 
