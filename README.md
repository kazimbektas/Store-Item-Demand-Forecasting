# Store-Item-Demand-Forecasting 

Using Times Series Model with LightGBM

<p align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQGw9EjWk-cNGuV1sjSTtxnfaKhoJKQRORpAg&s" alt="MasterHead"/>
</p>

## Project Overview

What's the best way to deal with seasonality? Should stores be modeled separately, or can you pool them together? Does deep learning work better than ARIMA? Can either beat xgboost?

## Business Problem

To predict NEXT 3 months of sales for 50 different items at 10 different stores.

This study aims to apply time series analysis techniques to predict future passenger volumes, utilizing a dataset that records monthly total airline passenger counts starting from 1949.

### Dataset Story

#### File descriptions
    
- **train.csv**: - Training data
- **test.csv**: - Test data (Note: the Public/Private split is time based)
- **sample_submission.csv**: - a sample submission file in the correct format


#### Data fields
    
- **date**: Date of the sale data. There are no holiday effects or store closures.
- **store**: Store ID - 10 different store
- **item**:Item ID - 50 different items
- **sales**: Number of items sold at a particular store on a particular date.


## Methods Used
- **Using Times Series Model with LightGBM**
- **SMAPE**


