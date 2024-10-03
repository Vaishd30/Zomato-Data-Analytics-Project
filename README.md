# Zomato-Data-Science-Project
This project gives an understanding of  the Zomato Data considered , the dataset was taken from kaggle. Exploratory Data Analysis has been performed and 6 potential questions have been answered.
1.What type of restuarant do majority of customers order from?
2.How many votes has each type of restaurant received?
3.What are the ratings that the majority of restaurants have received?
4.Zomato has obsereved that most of the couples order food online.What is their average spending?
5.Which mode (online or offline) has received the maximum ratings?
6.Which type of restaurant received more offline orders? So that zomato can provide customers with offer.

# Import libraries 
pandas for data manipulation and analysis, numpy for numerical operations,matplotlib and seaborn for data visualization.


# Create the Dataframe
In this case load the csv file.


# Perform Exploratory Data Analysis
EDA is performed to understand the variables, their relation with other variables, find any outliers , check for missing values and uncover patterns and trends in the data.
Here the datatype of the column "rate" is converted to float for better analysis.


1. Seaborn Countplot

Seaborn countplot is used in this case to get the exact count of number of customers ordering from each type of restaurant. From the countplot below we can conclde that   majority of the orders are from "Dining" type.

![Counplot](https://github.com/user-attachments/assets/b7fdb265-e65d-457c-a032-0c31f0481448)


2.Line Graph

To visualize the number of votes each restuarant received we use the line graph by first taking the summation and grouping the two columns "listed_in(type)" and "votes". From the graph below we can conclude that "Dining" type received the maximum number of votes.

![Line Graph](https://github.com/user-attachments/assets/f78b4cfb-57f6-4ebc-a5f3-03dbe6eff5db)


3.Histogram 

From the graph below we can conclude that majority of restuarnts have received rating between 3.5 and 4.

![Histogram](https://github.com/user-attachments/assets/616df367-fa3a-4807-9280-58204410f198)


4.Countplot

From the below plot we conclude majority of couples prefer restaurant with an approximate cost of Rs.300.

![Count plot 1](https://github.com/user-attachments/assets/fffec129-d724-4b91-ada0-88af1c2ba10f)


5.Boxplot

From the below graph we can conclude that offline order received lower rating in comparision to online rating.

![Boxplot](https://github.com/user-attachments/assets/a705424b-7f3f-49ea-b04a-e93ab60c2a31)

6.Heatmap

To generate a Heatmap a pivot table was created with the variables and we can conclude that Dining restuarnts primarily accept offline orders,whereas cafes primarily receive online orders. This suggests that clients prefer orders in person at restaurants, but prefer online ordering at cafes.

![Heatmap](https://github.com/user-attachments/assets/6a0e1bc8-da77-4193-82a6-aa9bc156131c)


# Conclusion
Various types of data analysis was performed from which one can get the idea of various plots and charts and an understanding of Exploratory Data Analysis. This can help the company modify it's strategy to retain and increase the number of customers.

 
# Resources
https://www.youtube.com/watch?v=XEMVDmyYkDU
https://www.kaggle.com/





   







