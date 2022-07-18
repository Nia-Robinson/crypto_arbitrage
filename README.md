# Project Title: Crypto Arbitrage

This is a Jupyter notebook that contains the code for the data collection, prepartion, and analysis of historical trade data for Bitcoin to determine if any arbitrage opportunities exist for Bitcoin.

Datasets:
bitstamp.csv (lower-priced exchange)
---
coinbase.csv (higher-priced exchange)

Early Date Period: 2018-01-16
---
Middle Date Period: 2018-02-24
---
Late Date Period: 2018-03-26

Final analysis:
In the early date time period the demand for bitstamp was low and the supply was high; by the middle and late dates the trend reversed and the demand for bitstamp was higher than the demand for coinbase. Profits were higher in the early time period compared to middle/late time periods. Also, during the earlier time period the cumulative profit was constant over time versus the cumulative profit for the middle/late time periods were only significant for a few hours.

![image](https://user-images.githubusercontent.com/34729547/179440999-459e9243-13f3-4826-8221-9c50e2861baf.png)

![image](https://user-images.githubusercontent.com/34729547/179441104-08d5709a-48a4-4840-a786-b1e701a7806d.png)

![image](https://user-images.githubusercontent.com/34729547/179441193-86e90612-00da-4e63-87ff-1530c24262bc.png)

---

## Technologies: Python 3, Jupyter Notebook

Python 3 or later.

Jupyter Notebook for IDE.

---

## Usage:

Ensure the proper libraries and dependencies have been imported
import pandas as pd
from pathlib import Path
%matplotlib inline


---

## Contributors: Nia Robinson

LinkedIn: https://www.linkedin.com/in/niaelanrobinson/

---

## License

MIT License.
