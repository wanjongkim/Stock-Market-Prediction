# Stock-Market-Prediction
This project comprises of machine learning using linear regression as well as time series analysis. The time series is a series of
data points in ordered time. The analysis was done by first taking a log from the cleaned data to lower the impact of the higher values.
Then I checked if the data was stationary by using the Dickey-Fuller test. Since the data was not stationary I used differencing to 
remove some of the seasionality and trend from the data. After that I used the ARIMA model to predict the future value of the stock.

# Data.csv
Inside this excel file you'll find three features. They include date, signal, and spy_close_price. 
The signal represents the abstract value that supposedly has an impact on the value of spy_close_price.
The spy_close_price is the value of the stock at the end of the day.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need to have the following:

```
Anaconda
```
```
Git
```

### Preparing

You can choose to install [Anaconda](https://www.anaconda.com/download/) or both python 3 and jupyter notebook.

Clone the project or download the project and unzip it. 

## Running the Project

Open up the Anaconda Navigator. From there launch the Jupyter Notebook. After few seconds, a browser will be opened that shows file directories.
Go to the directory that has the project files. Click on the Stock_Market_Prediction file to open it. From there, you simply have to
click on the arrow button on top to run each section of codes.

## Authors

* **Wan Jong Kim** - [Wan Jong Kim](https://github.com/wanjongkim)
