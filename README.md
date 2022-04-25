# Amazon_Vine_Analysis

# Overview of the analysis:
In this project, I will be choosing and accessing a specifc products data set, more specfically "apparel" is the product I would be looking into. I'm going to be using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then  I will be using Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

# Results:
-----------------------------------------------------------------------
## How many Vine reviews and non-Vine reviews were there?
<img width="453" alt="Screen Shot 2022-04-24 at 11 42 03 PM" src="https://user-images.githubusercontent.com/96555487/165022121-6b8fd51b-2ba6-42e3-b4d6-05726dc3e67b.png">

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
<img width="441" alt="Screen Shot 2022-04-24 at 11 42 57 PM" src="https://user-images.githubusercontent.com/96555487/165022187-ecca1701-e90c-4946-8aab-b7acef71e1c6.png">

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
<img width="438" alt="Screen Shot 2022-04-24 at 11 43 24 PM" src="https://user-images.githubusercontent.com/96555487/165022219-b49ab330-62b3-4d96-be5c-f45b112f8833.png">


# Summary: 
In summary, acccording to the data and statisitcs the vine program isn't worth the investment, at least for the apparel products. out of the 33 total only half had a five star review. So we can conclude that their isn't a positivity bias for reviews in the Vine program
