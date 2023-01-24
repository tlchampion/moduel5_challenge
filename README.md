# Financial Simulations and APIs

This is the Module 5 Challenge for the FinTech Bootcamp.

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


Alternatively, an existing environment can be used in which case both Jupyter Lab and python-dotenv must be installed. If now already done, both may be installed using pip

```
pip install jupyterlab
pip install python-dotenv

```


In addition, a .env file must be created in the root directory for this project containing the following two items:
* ALPACA_API_KEY
* ALPACA_SECRET_KEY

Personal api and secret keys may be obtained from the [Alpaca website](https://alpaca.markets).

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
