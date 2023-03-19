# Credit_Union_Planner
This is a jupyter notebook that uses API calls to analyza hypothetical returns and portfolio analysis'. This helps the desired user understand and evaluate their current financial standing(s). The user can view their cryptocurrency portfolio in addition to their stocks and bonds portfolio. The second half of the notebook assignment allows the user to observe their retirement health. They are able to view their health through the use of Alpaca API and a Monte Carlo simulation to view the possible outcomes of their portfolios.
---

## Technologies & Libraries
This assignment utilizes python 3.7 with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

*  [Numpy](https://github.com/numpy/numpy) - for entry point, and help page.

* [Dotenv](https://github.com/vlucas/phpdotenv) - reads .env files seperate from the environment.

* [Alpaca-api-call](https://github.com/alpacahq/alpaca-trade-api-python)-python library for the Alpaca Commission Free Trading API. 

* [Metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

---

## Pre Installation Guide

Prior to running the application and code, please install the following dependencies:

```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
%matplotlib inline
```

---

## Contributors

DU starter code

Ben Lindauer

MCForecastTools.py

Alpaca

---

## License

MIT
