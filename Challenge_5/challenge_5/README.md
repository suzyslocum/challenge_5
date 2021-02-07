# challenge_5
Module 5 challenge

# Financial Planning with APIs and Simulations

This is a python application written with Pandas in Jupyter Lab that uses the Requests library and makes an Alpaca API call in to retrieve the required data. In the first section, this data is used to determine the current value of a member’s cryptocurrency wallet and evaluate their emergency fund. In the second section we use the data to create a financial planner for retirement. 

![Savings Info](Challenge_5/Images/Screen Shot 2021-02-06 at 4.19.23 PM.png)

![Upper and Lower Bounds](Challenge_5/Images/Screen Shot 2021-02-06 at 4.41.38 PM.png)

![Upper and Lower Bounds Table](Challenge_5/Images/Screen Shot 2021-02-06 at 4.43.17 PM.png)

---

## Technologies

The application is written using Pandas

The following packages are used:

Pandas - to write and run the program [Pandas documentation](https://pandas.pydata.org/docs/)

Matplotlib - to create graphs [Matplotlib documentation](https://matplotlib.org/3.3.3/contents.html)

os - miscellaneous operating system interfaces [os documentation](https://docs.python.org/3/library/os.html)

Requests - to send http requests [Requests documentation](https://requests.readthedocs.io/en/master/)

Json - as an encoder and decoder [Json documentation](https://docs.python.org/3/library/json.html)

Dotenv - to read and add a key-value pair to an environment [Dotenv documentation](https://pypi.org/project/python-dotenv/)

Alpaca Trade API - to retrieve real-time stock and bond data [Alpaca documentation](https://alpaca.markets/docs/api-documentation/)

MCForecastTools - to use Monte Carlo simulations [MC Simulation documentation](https://pythonprogramming.net/monte-carlo-simulator-python/)

---

## Installation Guide

Install the Pandas package using the following command: 'import pandas as pd'

Install the Matplotlib library using the following command: '%matplotlib inline'

Install the os library using the following command: 'import os'

Install the Requests library using the following command: 'import requests'

Install the json library using the following command: 'import json'

Install the dotenv library using the following command: 'from dotenv import load_dotenv'

Install the Alpaca Trade API using the following command: 'import alpaca_trade_api as tradeapi'

Install the Monte Carlo Simulation package using the following command: 'from MCForecastTools import MCSimulation'


--- 

## Usage

To run this program, clone the repository onto your computer, navigate to its source folder in your terminal and launch it using the command 'jupyter lab' then either run the entire program at once, or run the cells individually (in order) as you move through the file.

---

## Contributors
Susannah Slocum suzyslocum@gmail.com

---

## License

MIT