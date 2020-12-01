# Sales-Analysis-Project
A mini project on sales analysis in python using Matplotlib, Pandas and Seaborn

## Objective  

Upon initial ispection of the data, we can start thinking of some questions about it that we would want to answer.
- What is overall sales trend?
- What are top 10 products by sale?
- What are most selling products?
- Which is the most preferred shipping mode?
- Which are profitable categories and sub categories?

### DATA AUDITING
We cannot work with the data until we know what are we dealing with, for example,
- Sales, Product name column
- Looking for any missing data
- Number of rows and so on.

![Screen Shot 2020-12-02 at 12 55 20 AM](https://user-images.githubusercontent.com/75334301/100787468-b33f9180-3439-11eb-83e9-3d7fc47e7870.png)

##  EXPLORATORY DATA ANALYSIS

WHAT IS OVERALL SALES TREND?
- Approach
1. Generate a new column with Year and Date in format (YYYY-MM)
2. Group all the Sales of the same Month and combine it with the above New Column
3. Plot the new dataframe with X axis as Month-Year and Y axis as COmbined Month Sales

Result :

![Screen Shot 2020-12-02 at 1 02 59 AM](https://user-images.githubusercontent.com/75334301/100787922-5ee8e180-343a-11eb-8e33-8c4319160e2e.png)

WHICH IS MOST PREFERRED SHIPPING MODE?
- Approach
1. Counting and grouping each Ship mode using Seaborn

Result :

![Screen Shot 2020-12-02 at 1 03 39 AM](https://user-images.githubusercontent.com/75334301/100789500-893b9e80-343c-11eb-9e53-b71c8259ada3.png)

WHICH ARE PROFITABLE CATEGORIES AND SUB-CATEGORIES?
- Approach
1. Filter out a new data set with categories, its sub Categories and the respective Profits
2. Sort the data in descending order.

Result : 

![Screen Shot 2020-12-02 at 1 03 54 AM](https://user-images.githubusercontent.com/75334301/100789508-8e005280-343c-11eb-9fd6-98395d36bb1c.png)

