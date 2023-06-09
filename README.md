# Flight Delay Predictions Applying Machine Learning

## About this project:

Delayed flights can have significant negative economic impacts on airlines, airports, and passengers which motivates the creation of more robust 
delay management programs like the existing FAA ground delay program (GDP). This project consists of two parts: analyzing flight & weather datasets, 
and predicting flight delays. One dataset has a year’s worth of all US flight delay info [retrieved from Kaggle](https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv/) and the other dataset has been gathered.
by web-scraping [weather site](https://www.wunderground.com/history/). We implemented a model to predict weather-induced airline delays using ML algorithm Random Forest.

## Installation - Video Demo

Click this link to go to the
[Youtube Video Demo](https://youtu.be/ShbRHaTKp_E)

## Description

This project contains 2 folders:

- DOC contains  the project's final report
- CODE contains the files necessary to run the web applications

## Installation

1. Install Python3 on local machine
2. Use the following commands to install necessary packages:

```python
pip install sklearn
pip install streamlit
pip install requests
pip install streamlit_lottie
pip install seaborn
```

## Execution

1. Navigate to code folder
2. Execute the following command: <code>streamlit run app_analytics.py</code>, this opens a web page on your local host that displays vizualiations related to our project
3. Execute the following command: <code>streamlit run app_prediction.py</code>, this opens an interactive user interface that allows the user to select predictor values then click on "predict" to get the prediction from the Machine Learning model.
4. It is important to note that there might "gray overlap" on the screen as the user makes selection  and a "running" icon  to the top right of the screen. The user can still continue to make selections even if the running icon is still active.

## Datasets & Files

- Original flights dataset from [Kaggle](https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv/)
- [flight_delay.pkl](https://gatech.box.com/s/20fkdrgzh00hlgqcz0mfuwm1tc5vinjp) is a file to utilize a pre-trained ML model in Streamlit. 

## Tech:

- Python 3
- scikit-learn - Linear Regression
- numpy
- pandas
- matplotlib
- seaborn
- pickle
- imblearn
- streamlit
- Tableau

## Authors:
Fidel Garcia | Theodore Cox | Winnie Messa | Wendy Navarrete


