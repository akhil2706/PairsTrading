# PairsTrading

A statistical arbitrage based pairs trading strategy is developed. In this project, cointegration between a pair is tested and the resultant spread is fit to an Ornstein Uhlenbeck process. Based on the parameters of the OU process, a trading strategy is determined for the pair. The strategy parameters are optimised on historical trading. This projects also supports a dynamic cointegration strategy. The dynamic strategy is developed using Kalman Filters.

## Getting Started 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites 

This project requires a Python2.7 environment with the following dependencies: 
1) Pandas 
2) Numpy
3) SciPy
4) Matplotlib
5) Statsmodels
6) Sklearn
7) PyFolio 

### Installation

The code for the strategy has been implemented in the .ipynb file included in the repository and can be replicated with the consent of the contributors.

## Testing 

The IPython notebook containts the code and the descriptive comments which debrief about the functionality of each function used. To begin implementation, run the 'trading_algorithm()' function. This is an interactive function which requires user input and based on it. The historic data is present in the 'data' folder. More recent data can be fetched from financial data providing websites for 'Yahoo Finance'. 

## Contributors 

Akhil Sethia


instructions will help you understand how to test the strategy defined in the underlying project. 
