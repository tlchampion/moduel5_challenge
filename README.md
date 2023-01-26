# Financial Simulations and APIs

This is the Module 5 Challenge for the FinTech Bootcamp.

The notebook consists of two sections:

* Part 1: A financial planner for emergencies. The user will be able to use this tool to visualize their current savings. The user can then determine if they have enough reserves for an emergency fund.

* Part 2: A financial planner for retirement. This tool will forecast the performance of a retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations. The 30 year will then be compared to a more aggressive portfolio on a 10 year timeframe. 


---

## Technologies

All code is contained within the included jupyter lab notebook. 

Python version 3.9.15 was used to complete this challenge. 

---

## Installation Guide

A working python environment is required. The included environmnet.yml file can be used to create a conda environment:

```
conda env create -f environment.yml

```


Alternatively, an existing environment can be used in which case both Jupyter Lab and python-dotenv must be installed along with watermark. If now already done, both may be installed using pip

```
pip install jupyterlab
pip install python-dotenv
pip install watermark

```


In addition, a .env file must be created in the root directory for this project containing the following two items:
* ALPACA_API_KEY
* ALPACA_SECRET_KEY

Personal api and secret keys may be obtained from the (Alpaca website)[https://alpaca.markets].

---

## Usage

The included .ipynb file should be opened in Jupyter Lab, which can be started in the configured python environment

```
jupyter lab

```

Details on using Jupyter Lab are beyond the scope of this project. Please consult the [Jupyter Lab documentation]
(https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html) for usage details.


---

## Contributors

Code framework provided by FinTech Bootcamp.
Code completion by Thomas L. Champion.

---

## License

License information can be found in the included LICENSE file.
