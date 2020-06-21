# Mod-2-project
This is the mod 2 project repository. 

## Brief Background
Diamonds are commonly seen jewelry and are luxuries to most people. People save money to purchase for important events in life. We all know that diamonds' prices are determined by size, clarity, color, etc. But how to determine the price for a diamond? When purchasing, people usually make serious considerations since it is big spent money.

## My Aim: 
The aim of this project is to analyze diamonds features and diamonds prices, find out how different features can influence the price, and build up a price prediction model to predict the prices of diamonds. After getting prediction model, use the model to check if online diamonds retailer website are overcharging people or give more economic/affordable choices.__

## Resources: There are 2 resources of data:
--(1) __Kaggle.com dataset__, prediction model will be build up based on this dataset; 
--(2) __Web scraping diamonds data from www.bluenile.com__ , data from www.bluenile.com will be compared to predictions. 

## This repository contains the following files:

*  mod2 project1.ipynb, -- the main jupyter notebook containing 6 parts: 1). 1. Data Collection and cleaning; 2). Explanatory Data Analysis, descriptive statistics; 3). Hypothesis Testing; 4). Model with MultipleLinear Regression and Lasso Regression, Comparing Models; 5). Feature Engineering, Establishing Final Model; 6). Business/Social Case & Conclusions. All EDA graphes are in this notebook; final model is in section 5; and each section has conclusion, and, final conclusions are made as summarized to seven points in last section. 

*  selenium webscraping.ipynb, -- I wrote web scraping code in this notebook to get data from online jewelry sales website. In this, various feature values can be input to scrape the data in the range I desire. 

*  diamonds.csv, -- the dataset downloaded from kaggle.com, I used this dataset to establish my prediction model. 

*  bluenile.csv, -- the data I scraped from www.bluenile.com, saved as .csv file. 

*  geckodriver.exe -- the file needed to run selenium scraping, to open firefox browser. 

*  diamondpredict.sav -- the final prediction model I saved using pickle, for future use.



