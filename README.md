# Financial Planning Tools

This program is a financial planner for:
* Emergencies. Use this tool to visualize current savings and then determine if enough reserves are available for an emergency fund
* Retirement. This tool can forecast the performance of retirement portfolios over a 30 year period. Forecasting is made possible by making an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For DataFrame construction and data sorting.

* [%matplotlib](https://github.com/matplotlib/matplotlib) - For data vizualization.

* [os](https://docs.python.org/3/library/os.html)

* [requests](https://realpython.com/python-requests/) - For accessing data via APIs

* [json](https://docs.python.org/3/library/json.html) - Reorganizes data from APIs in to a readable format.

* [dotenv](https://pypi.org/project/python-dotenv/)

* [alpaca_trade_api_python](https://github.com/alpacahq/alpaca-trade-api-python/) 

---

## Installation Guide

Before running the application first install the following dependencies.


```python
  pip install pandas
  pip install %matplotlib
  pip install python-dotenv
  pip install alpaca-trade-api
```

---

## Contributors

Quintin Bland

---

## License

MIT
