# Diamonds Price Prediction and Feature Analysis

## Brief Background
Diamonds are valuable jewels and well hold their values. People preserved diamond jewelry for very long time after purchase. We all heard about some diamonds' attributes like size, clarity, etc, but how are diamonds' values (price) determined? Nowadays, there are online diamonds retail websites. Are those online stores better choices? People usually make serious considerations since it is big money.

## My Aim: 
1. The goals of this project are to establish machine learning model to predict diamonds prices, and use the model to check if online diamonds retailer websites have better prices or overcharge people.
2. In this project, various attributes of diamonds are analyzed by EDA, descriptive statistics and statistical tests to see how they influence values of diamonds. Also, prediction models are evaluated by RMSE and Z-Score to get the best model.

## Resources: There are 2 resources of data:
--(1) __Kaggle.com dataset__, prediction models are built up based on the dataset from Kaggle; 
--(2) __Web scraping diamonds data by Selenium from www.bluenile.com__ , diamonds' features and prices data from www.bluenile.com are scraped and evaluated with the machine learning model

## This repository contains the following files:

*  DiamondPricePredictionandFeatureAnalysis.ipynb, -- the main jupyter notebook containing 6 parts: 1). Data collection, web scraping, data cleaning; 2). Exploratory data analysis, descriptive statistics; 3). Hypothesis testing; 4). Model fitting with multiple linear regression and lasso regression, evaluate models; 5). Futher feature engineering, model improvement; 6). Business/social case analysis & conclusions. 

*  selenium webscraping.ipynb, -- Web scraping code in this notebook to get data from online jewelry sales website. In this, various feature values can be input to scrape the data in the range I desire. 

*  diamonds.csv, -- the dataset downloaded from kaggle.com, I used this dataset to establish my prediction model. 

*  bluenile.csv, -- the data I scraped from www.bluenile.com, saved as .csv file. 

*  geckodriver.exe -- the file needed to run selenium scraping, to open firefox browser. 

*  diamondpredict.sav -- the final prediction model I saved using pickle, for future use.

## Some conclusions: 

* In the diamonds market, prices are like exponentially related to carat weight, as the carat weight get larger and larger, price increase faster and faster. One 2 carats diamond are much valuable than 2 one carat diamonds. This relationship is shown in the following plot:
![image](https://user-images.githubusercontent.com/64159084/92063971-6b419d80-ed6a-11ea-8d6b-96dafa9d62f9.png)

* In reality, top quality diamonds(higher clarity, higher colorless) mainly lay in smaller diamonds range, it is difficult to get larger carat weight high clarity (or high color level) diamonds. Bigger diamonds are more likely to have middle or low clarity or colorless levels. This fact can be demonstrated in the following 2 plots:
![image](https://user-images.githubusercontent.com/64159084/92064144-e1460480-ed6a-11ea-9bdf-67c5df07fa9d.png)
![image](https://user-images.githubusercontent.com/64159084/92064154-ea36d600-ed6a-11ea-9cbc-ec26b05b2149.png)

* Pure dimensions (x,y,z) of diamonds are usually not cared in diamonds selection, since carat weight value can represent them. But the shape matters, the L/W and depth are important features that can affect diamonds prices.

* Overall speaking, middle color level and middle clarity level have the most percentage in all levels.

* There is statistically significant difference in carat weight of diamonds with different cut levels, there is statistical significant difference in prices of diamonds with different color levels.

* There is relationship between the distributions of diamond clairity levels category and the color levels category (they are not independent), this is determined by diamonds forming mechanism and processing underground.

* Prediction model developed with Kaggle dataset can predict the diamonds' prices accurately with data in kaggle dataset. But when predicting prices of diamonds on online retailers' websites, results are higher than online sales prices. Nevertheless, we can clearly see that the trends are similar. Normally, online sales prices are lower, this makes sense. And, datasets from different resources many not reflect each other very well. 

## Project presentation link:

https://docs.google.com/presentation/d/1YXuIXfcZhcGVjATO_c1_hLBSJ684fRFyFeLu2MA_zYQ/edit?usp=sharing
