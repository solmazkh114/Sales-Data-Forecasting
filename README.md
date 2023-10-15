# Sales Data Analysis and Forecasting

In this project we aim to explore the [Kaggle Store Sales- Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview) data to
extract insight and hidden patterns and train some machine learning models to forecaste customer demands for the 15 next days. This Dataset contians stores sales data of an Ecuadorian grocery
retialer. It contians data of 33 category of products within 54 branches across the country. 

This repository contians 4 main files:

- EDA on StoreSale Data: This notebook starts with loading all data files one by one and exploring them. Then we will merge all data to create a unique dataframe for furthure investigation.
  Then we will start exploring the dataframe by various visualizations.
- EDA on StoreSale Data- Series based: This notebook starts with creating a flat form of all time series 1782 (=33*54) series. This way of accessing each series makes the process of some
  analysis more easy.
- EDA on StoreSale Data- Time features: This note book in the continuation of the first notebook where we will explore time based features and trand and seasonlity of some of time series
  within data.
- Model Training: In this notebook,  we are going to train ML models using the Darts library on this dataset. At first, we will consider one series and train models on just one series.
  Then we will group the whole data based on their families and train Darts’ model on a list of time series all included in one family. Based on
  [this notebook](https://unit8co.github.io/darts/examples/01-multi-time-series-and-covariates.html), this type of training, when a model sees other series while training, can improve
  the performance of the model. Actually, the model will learn trend and seasonality within other time series which result in better performance.


  
