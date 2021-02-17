# Boston House Price Prediction Using Machine Learning

This project is created to host the files required for the first project of Udacity's Nanodegree Program.
The data used for this project comes from AirBnB Boston Dataset found here: https://www.kaggle.com/airbnb/boston
The main findings of this project can be found at the blog post available here: 

## Motivation for the project

We wish to predict house prices using the listings data. The reason for this is centered around the home owner's perspective who wishes to host people in his house. He might wish to know a few things about the market before commiting to a certain price for his home. Of the things he should know, the following questions were addressed here with a brief answers:

   - Question 1: How deciding is he location of the property in the price the owner should demand

The geographical location of the home was the single most deciding factor when predicting the price of a home. In fact, 7 out of the 10 most important features were related to the geographical location of the property. 
            
   - Question 2: What characteristics of the home itself are important on deciding this price and how important are they?

Quite surprisingly, the main characteristics of the home such as number of bedrooms, number of bathrooms, and the people the house accommodates are not deciding factors. In fact, the most important of those characteristics is the number of bedrooms placed at the 76th spot in ranking of importance.

   - Question 3: Is it possible to predict the adequate listing price for the property and, if so, with how much accuracy?

The model is adequate to predict log_prices as can be seen in the graph below showing actual vs predicted values

![Test_actual_vs_predicted](https://user-images.githubusercontent.com/46632664/108276634-1a6e0780-7146-11eb-8ffc-021e73497ed8.PNG)

From the metric point of view, the model reaches a R2 metric of 0.667 which, although not high, is sufficient.

These questions are important because an undervalued property could attract clients but not be able to pay for its expenses while and overvalued property could have the opposite bad effects

## This Repository
The project has the two following files
   - listings.csv : The AirBnB Boston Dataset in .csv format available on Kaggle.com in the link above
   - udacity-boston.ipynb : Jupyter notebook having the complete analysis done on the data

