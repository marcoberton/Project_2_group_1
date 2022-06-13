# Algorithmic trading 

This application automates the process of trading assets by leveraging a Bollinger Band strategy that executes trades once "buy" or "sell" conditions are met.

## Purpose
Our goal is to create an algorithmic trading strategy combined with a forward looking machine learning model generated using FB Prophet. To do this we are using current/historic stock data of Microsft "MSFT". The sources we are analyzing are Alpaca and Yahoo Finance. This program leverages the power of Python and Pandas to collect, prepare, and analyze neccessary data. First, it uses APIs to get the latest price data. Next, it cleans the data and consolidates relevant information into a DataFrame. Then it feeds the data to FB Prophet to generate a prediction. Then we apply Bollinger Bands to the prediction which is used by our strategy to make buy/sell signals for the next day. Time permitting, we'll then feed this to a trading bot to make an order to a paper trading API.  

## Files

- Data Prep - "..\Project_2\Project_2_group_1\data_prep.ipynb"
- Machine Learning FB Prophet - "..\Project_2\Project_2_group_1\ml_strategy.ipynb"
- Bollinger Bands - "..\Project_2\Project_2_group_1\Algorithm_strategy.ipynb"

## Technologies  
  
Python, Pandas Library, Anaconda Jupyter Lab, Alpaca, yfinance, fbprophet  
  
## Installation Guide
•	Install Python (Refer python installation guide) Pandas Library, Anaconda Jupyter Lab.  
•	Install Anaconda  
•	Install Jupiter Lab  
Install required libraries such as fbprophet, Alpaca, yfinance  
•	checkout git repository  
•	navigate to the folder through Jupyter Lab  


## Usage

1.	Navigate .."C:\Users\ahmed\desktop\Challenge_Folder\Project_2\Project_2_group_1" through Jupyter Lab  
2.	run All cells  
3.	Models and plots will be displayed inline  
  
## Contributors  
  
- Fadiya Ahmed  
- Marco Bertone  
- James Miller  
- Morgan Blackmore  

---
  
## License  
  
GPL License  
