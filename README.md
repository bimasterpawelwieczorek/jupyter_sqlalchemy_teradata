# Jupyter sqlalchemy teradata
Connect to Teradata Database with Teradata Wallet, sqlalchemy, %sql magic, plotly, widgets

## What you need

Python packages:
```python
python -m pip install jupyter teradata pandas sqlalchemy-teradata ipython-sql plotly
``` 

Teradata ODBC client. In my example *Teradata Database ODBC Driver 16.10*

*Make sure that decimal point in Windows settings is dot not comma (like in Polish language) otherwise it casts decimal values to NaN.*

Sample data: https://github.com/dnoeth/payroll_sample_tables_for_Teradata
