# Bigmart_prediction

# Problem statement:

The problem statement is to build a predictive model to determine the sales of each product at a particular store using the provided sales data for 1559 products across 10 stores in different cities, along with certain attributes of each product and store.

The aim is to develop a model that can accurately predict sales, which can help in identifying factors that drive sales and improve business decisions.

# Dataset :https://training.github.com/downloads/github-git-cheat-sheet.pdf

# Hypothesis Generation:

1.)Brand: Branded products have more trust of the customers so they should have high sales

2.)City type: Stores located in urban cities should have higher sales.

3.)Population density:Densely populated areas have high demands so the store located in these areas should have higher sales.

4.)Marketing: Stores having a good marketing division can attract customers through the right offers.

5.)Visibility in Store: The location of the product placement also depends on the sales.

6.)Utility: Daily use products have a higher tendency to sell compared to other products.

7.)Packaging: Quality packaging can attract customers and sell more.


# summary:

The Bigmart Sales dataset is a fictional dataset that contains information on sales data for various products sold at different stores of Bigmart stores. The dataset contains information on the sales of 1559 products across 10 different stores for the year of 2013.

The dataset includes variables such as Item_Identifier, Item_Weight, Item_Fat_Content, Item_Visibility, Item_Type, Item_MRP, Outlet_Identifier, Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type, Outlet_Type, and Item_Outlet_Sales.

First importing the required libraries and load the datasets.

Now identify is there any missing values  or not in the dataset.If there is any missing values in the dataset we have to fill the missing values using statical techniques or machine learning models.

Now convert the categorical attributes to numerical attributes for machine learning model can identify uniquely.

Now we apply the data visuallization using the matplotlib and seaborn libraries.

Now split into training and testing data
and train the training data and using testing data we predict accuracy of upcoming sales by using Regression models.

Here some of the regression models

1.)LinearRegression

2.)RandomForestRegression

3.)XGBoostRegression

Here out of 3 models I predict the best accuracy in RandomForestRegression.

The Accuracy is 55.74644934253331
