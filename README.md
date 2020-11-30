# Udacity-Project-1-Boston-AirBNB
This project is created to host the files required for the first project of Udacity's Nanodegree Program.

The notebook has the following sections commented in markdown cells

## 1. Reading the Data: 
Apart from reading the required datasets, this step talks about the motivation behind choosing this dataset and the business questions that will be addressed.

   We wish to predict house prices using the listings data. The reason for this is centered around the home owner's perspective who wishes to host people in his house. He might wish to know a few things about the market before commiting to a certain price for his home. Of the things he should know, the following will be addressed here:
   
- How deciding is he location of the property in the price the owner should demand
- What characteristics of the home itself are important on deciding this price and how important are they?
- Is it possible to predict the adequate listing price for the property and, if so, with how much accuracy?
These questions are important because an undervalued property could attract clients but not be able to pay for its expenses while and overvalued property could have the opposite bad effects
## 2. Numerical Variables
   After loading the data, the numerical variables are separated for their transformation consisting of two steps:
   - Columns with a high percentage of missing values are removed,
   - Columns with a very high correlation with other columns are removed. This high degree of correlations is considered when it is above 0.9
   - Columns are imputed using their mean
## 3. Categorical Variables
   Categorical variables are loaded and transformed. Special care here is taken due to the following considerations
   - Some numerical variables are recognized as categorical due to them having special characters in their cells such as '$' or '%',
   - Some columns being large strings of text containing miscellaneous information such as urls, reviews, names, etc which, in principle, don't have a well defined meaning or predictive value, or simply they would need of NLP techniques to be useful. This columns are removed,
   - Some of the columns have too many levels making the regression task almost impossible (in the order of hundreds, even thousands) while some have only one level. This columns are removed.
## 4. Exploration
   The exploration analysis attempts to solve the majority of the questions posed in the first section. The analysis is mainly a graphical one, mainly with the help of correlation heatmaps and plots of grouped quantities.
## 5. Modeling and Results
   A linear regression model (sklearn) is applied to attempt to consolidate the results found so far as well as gaining more insight into the deciding factors affecting the listing price.
