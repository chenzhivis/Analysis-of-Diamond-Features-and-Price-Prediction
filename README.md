# Mod-2-project
This is the mod 2 project repository. 

__My Aim: The aim of this project is to analyze diamonds features and diamonds prices, find out how different features can influence the price, and build up a price prediction model to predict the prices of diamonds. After getting prediction model, use the model to check if online diamonds retailer website are overcharging people or give more economic/affordable choices.__

__Resources: There are 2 resources of data:__
--(1) __Kaggle.com dataset__, prediction model will be build up based on this dataset; 
--(2) __Web scraping diamonds data from www.bluenile.com__ , data from www.bluenile.com will be compared to predictions. 

This repository contains the following files:

## 1. mod2 project1.ipynb, -- the main jupyter notebook containing 6 parts: 1). 1. Data Collection and cleaning; 2). Explanatory Data Analysis, descriptive statistics; 3). Hypothesis Testing; 4). Model with MultipleLinear Regression and Lasso Regression, Comparing Models; 5). Feature Engineering, Establishing Final Model; 6). Business/Social Case & Conclusions. All EDA graphes are in this notebook; final model is in section 5; and each section has conclusion, and, final conclusions are made as summarized to seven points in last section. 

## 2. selenium webscraping.ipynb, -- I wrote web scraping code in this notebook to get data from online jewelry sales website. In this, various feature values can be input to scrape the data in the range I desire. 

## 3. diamonds.csv, -- the dataset downloaded from kaggle.com, I used this dataset to establish my prediction model. 

## 4. bluenile.csv, -- the data I scraped from www.bluenile.com, saved as .csv file. 

## 5. geckodriver.exe -- the file needed to run selenium scraping, to open firefox browser. 

## 6. diamondpredict.sav -- the final prediction model I saved using pickle, for future use.



