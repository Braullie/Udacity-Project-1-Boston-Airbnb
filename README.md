# Udacity-Project-1-Boston-AirBNB
This project is created to host the files required for the first project of Udacity's Nanodegree Program.

The notebook has the following sections commented in markdown cells

## 1. Reading the Data: 
   Apart from reading the required datasets, this step talks about the motivation behind choosing this dataset and the business questions that will be addressed.
## 2. Numerical Variables
   After loading the data, the numerical variables are separated for their transformation consisting mainly of 
## 3. Categorical Variables
   Categorical variables are loaded and transformed. Special care here is taken due to the following considerations
   - Some numerical variables are recognized as categorical due to them having special characters in their cells such as '$' or '%',
   - Some columns being large strings of text containing miscellaneous information such as urls, reviews, names, etc which, in principle, don't have a well defined meaning or predictive value, or simply they would need of NLP techniques to be useful. This columns are removed,
   - Some of the columns have too many levels making the regression task almost impossible (in the order of hundreds, even thousands) while some have only one level. This columns are removed.
## 4. Exploration
   The exploration analysis attempts to solve the majority of the questions posed in the first section. Here 
## 5. Modeling and Results
   A linear regression model (sklearn) is applied to attempt to consolidate the results found so far as well as gaining more insight into the deciding factors affecting the listing price.
