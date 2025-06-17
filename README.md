Welcome to the repository: Time Series Forecasting: Store Sales

In this repository, I forecast grocery store sales using different machine learning techniques. This project is based on the Kaggle competition "Store Sales - Time Series Forecasting". (https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview)

I predict the sales using data from Corporación Favorita, a large Ecuadorian-based grocery retailer. This data can either be downloaded from the above link or by downloading and extracting the files from "store-sales-time-series-forecasting.ipynb".

The repository contains two notebooks, fit_linearregression.ipynb and fit_hybrid.ipynb. 

In the first one, fit_linearregression.ipynb, I fit the time series using only one method, i.e, linear regression. In this analysis, I deal with categorical features using one-hot encoding. 

In the second notebook, fit_hybrid.ipynb, I fit the time series using two different machine learning models, namely linear regression and Random Forest. In this analysis, I use linear regression to model the temporal dependence and random forest to model the other features. Adding the predictions through this hybrid approach leads to better results.  

The temporal features (trend and seasonality) are modelled in both notebooks using a linear increase in time (overall trend) and two Fourier components of yearly and weekly frequencies (seasonality). 
In the second notebook, categorical features are dealt with using label encoding, as opposed to one-hot encoding in the first case. 

Once the data is downloaded (and stored in the same directory as the notebooks) and the necessary packages have been installed, the notebooks can be directly run. 
