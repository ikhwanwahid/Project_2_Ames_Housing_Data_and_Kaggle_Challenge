# Project 2 - Ames Housing Data and Kaggle Challenge

Welcome to Project 2! It's time to start modeling.

**Primary Learning Objectives:**
1. Creating and iteratively refining a regression model
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process
3. Providing business insights through reporting and presentation.

You are tasked with creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale.

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

Secondly, we are hosting a competition on Kaggle to give you the opportunity to practice the following skills:

- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science

As always, you will be submitting a technical report and a presentation. **You may find that the best model for Kaggle is not the best model to address your data science problem.**


**Problem Statement:**
<br>We the good people property agents of WAN house for you have decided to find the best <br>model in prediction house prices in the Ames area. You give us a price in mind, we <br>give you what you can afford to have. 
<br>Already know what you want, let us know and we will give you the estimated price of <br>your house!!

**Executive Summary**
<br>Contents:
<br>Importing the Relevant Libraries
<br>Loading the Data
<br>Cleaning the Data
<br>Testing the idea of VIF to reveal collinearity between numerical features
<br>Testing the idea of CHI-SQUARE test to reveal relationships between categorical features
<br>Finding our 𝑅2 with the linear regression
<br>Find an optimal value for the ridge regression alpha usingRidgeCV.
<br>Cross-validate the ridge regression 𝑅2 with the optimal alpha.
<br>Find an optimal value for lasso regression alpha using LassoCV.
<br>Cross-validate the lasso 𝑅2 with the optimal alpha.
<br>Look at the coefficients for variables in the lasso.
<br>Find an optimal value for elastic net regression alpha using ElasticNetCV.
<br>Cross-validate the elastic net 𝑅2 with the optimal alpha and l1_ratio.
<br>CLEANING AND FITTING OUR MODEL to acual TEST values!!
<br>Final Thoughts and Conclusion