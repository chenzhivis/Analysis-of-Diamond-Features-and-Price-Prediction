# Analysis of Diamond Attributes and Price Prediction

## Brief Background
Diamonds are commonly seen jewelry and are luxuries to most people. People save money to purchase for important events in life. We all know that diamonds' prices are determined by size, clarity, color, etc. But how to determine the price for a diamond? When purchasing, people usually make serious considerations since it is big spent money.

## My Aim: 
1. The goals of this project are to establish machine learning model to predict diamonds prices, and use the model to check if online diamonds retailer websites have better prices or are overcharging people.
2. In this project, various attributes of diamonds are analyzed by EDA, descriptive statistics and statistical tests to see how they influence values of diamonds. Also, prediction models are evaluated by RMSE and Z-Score to get the best model.
3. There are 2 resources of data: --(1) Kaggle.com dataset, prediction model will be build up based on this dataset; --(2) Web scraping diamonds data from www.bluenile.com , I will use the prediction model to predict prices of diamonds on www.bluenile.com, compare the prediction results with the prices listed on the website.

## Resources: There are 2 resources of data:
--(1) __Kaggle.com dataset__, prediction models are built up based on the dataset from Kaggle; 
--(2) __Web scraping diamonds data from www.bluenile.com__ , diamonds' features and prices data from www.bluenile.com are scraped and evaluated with the machine learning model

## This repository contains the following files:

*  mod2 project1.ipynb, -- the main jupyter notebook containing 6 parts: 1). Data collection, web scraping, data cleaning; 2). Exploratory data analysis, descriptive statistics; 3). Hypothesis testing; 4). Model fitting with multiple linear regression and lasso regression, evaluate models; 5). Futher feature engineering, model improvement; 6). Business/social case analysis & conclusions. 

*  selenium webscraping.ipynb, -- I wrote web scraping code in this notebook to get data from online jewelry sales website. In this, various feature values can be input to scrape the data in the range I desire. 

*  diamonds.csv, -- the dataset downloaded from kaggle.com, I used this dataset to establish my prediction model. 

*  bluenile.csv, -- the data I scraped from www.bluenile.com, saved as .csv file. 

*  geckodriver.exe -- the file needed to run selenium scraping, to open firefox browser. 

*  diamondpredict.sav -- the final prediction model I saved using pickle, for future use.

## Some conclusions: 

* In the diamonds market, prices are like exponentially related to carat weight, as the carat weight get larger and larger, price increase faster and faster. One 2 carats diamond are much valuable than 2 one carat diamonds.

* In reality, top quality diamonds(higher clarity, higher colorless) mainly lay in smaller diamonds range, it is difficult to get larger carat weight high clarity (or high color level) diamonds. Bigger diamonds are more likely to have middle or low clarity or colorless levels

* Pure dimensions (x,y,z) are usually not cared in diamonds selection, since carat weight value can represent them. But the shape matters, so L/W and depth are important features that can affect diamonds prices.

* Overall speaking, middle color level and middle clarity level have the most percentage in all levels.

* There is statistically significant difference in carat weight of diamonds with different cut levels, there is statistical significant difference in prices of diamonds with different color levels.

* There is relationship between the distributions of diamond clairity levels category and the color levels category (they are not independent), this is determined by diamonds forming mechanism and processing.

* Prediction model developed based on Kaggle dataset fit perfectly with Kaggle dataset, but predict higher prices than online sales prices. Normally, online sales prices are lower, this makes sense. And, datasets from different resources many not reflect each other well. Data resources of learn and practices (non-profit) may not have the same trend as data from commercial resources. Before using dataset to make serious modeling and professional prediction, reliability of data resources and type of the data resources shall be considered.

## Project presentation link:

https://docs.google.com/presentation/d/1YXuIXfcZhcGVjATO_c1_hLBSJ684fRFyFeLu2MA_zYQ/edit?usp=sharing
