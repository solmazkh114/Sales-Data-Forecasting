# Sales Data Analysis and Forecasting

In this project we aim to explore the [Kaggle Store Sales- Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview) data to
extract insight and hidden patterns and train some machine learning models to forecast customer demands for the 15 next days. This Dataset contains stores sales data of an Ecuadorian grocery
retailer. It contains data of 33 categories of products within 54 branches across the country. 

This repository contains 4 main files:

 - EDA on StoreSale Data: This notebook starts with loading all data files one by one and exploring them. Then we will merge all data to create a unique dataframe for further investigation. Then we will start exploring the dataframe through various visualizations.
 - EDA on StoreSale Data- Series based: This notebook starts with creating a flat form of  all the time series 1782 (=33*54) series. This way of accessing each series makes the process of some analysis more easily.
 - EDA on StoreSale Data- Time features: This notebook in the continuation of the first notebook where we will explore time-based features and trends and seasonality of some of the time series within data.
 - Model Training: In this notebook,  we are going to train ML models using the Darts library on this dataset. At first, we will consider one series and train models on just one series.
  Then we will group the whole data based on their families and train Darts’ model on a list of time series all included in one family. Based on
  [This notebook](https://unit8co.github.io/darts/examples/01-multi-time-series-and-covariates.html), this type of training, when a model sees other series while training, can improve
  the performance of the model. Actually, the model will learn trend and seasonality within other time series which result in better performance.

  In these notebooks, we use some of the techniques and methods we learned about them in the following two Kaggle notebooks:

   - [Notenbook 1](https://www.kaggle.com/code/chongzhenjie/ecuador-store-sales-global-forecasting-lightgbm)
   - [Notebook 2](https://www.kaggle.com/code/ferdinandberr/darts-forecasting-deep-learning-global-models)


  
