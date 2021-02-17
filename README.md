# Boston AirBNB House Price Analysis Using Machine Learning

This project is created to host the files required for the first project of Udacity's Nanodegree Program.  

The data used for this project comes from AirBnB Boston Dataset found here: https://www.kaggle.com/airbnb/boston  

The main findings of this project can be found at the blog post available here: https://smurguersons.medium.com/price-prediction-in-boston-airbnb-6de2799c2f92  

**Table of Contents**
   1. Installation
   2. Project Motivation
   3. File Description
   4. Results
   5. Licensing, Authors, and Acknowledgements

## Installation
The project was done on a Kaggle.com Python notebook. The following libraries were used
   - numpy
   - pandas
   - seaborn
   - matplotlib
   - scikit-learn


## Motivation for the project

We wish to predict house prices using the listings data. The reason for this is centered around the home owner's perspective who wishes to host people in his house. He might wish to know a few things about the market before commiting to a certain price for his home. Of the things he should know, the following questions were addressed here with a brief answers:

   - Question 1: How deciding is he location of the property in the price the owner should demand
            
   - Question 2: What characteristics of the home itself are important on deciding this price and how important are they?

   - Question 3: Is it possible to predict the adequate listing price for the property and, if so, with how much accuracy?

These questions are important because an undervalued property could attract clients but not be able to pay for its expenses while and overvalued property could have the opposite bad effects

## File Descriptions
The project has the two following files
   - listings.csv : The AirBnB Boston Dataset in .csv format available on Kaggle.com in the link above
   - udacity-boston.ipynb : Jupyter notebook having the complete analysis done on the data

## Results

It was found that the most important factor deciding the price of a home posted on AirBnB was the geographical location. When implementing a linear regression model, out of the 10 most important factors, 7 were about location and the other 3 were related to the listing and not the home itself. As a matter of fact, the home characteristics such as number of bedrooms were relegated to the spot 76 and beyond. The complete results are available on the **medium blog link posted above.**

## Licensing, Authors, Acknowledgements

Credit is given to AirBnB for posting the data to the public and to Kaggle for hosting it and giving users the opportunity to access it in their notebooks. All licensing and information about the data can be found here: https://www.kaggle.com/airbnb/boston. 

Special acknowledgement and thanks is given to GitHub user jjrunner whose readme file inspired this one. It can be found here: https://github.com/jjrunner/stackoverflow
