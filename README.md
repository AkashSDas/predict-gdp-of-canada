# Predict-GDP-of-Canada  


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)

[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)

  
  

## Table of contents

  

*  [About](#about)

*  [Installation](#installation)

*  [Data Source](#data-source)

*  [License](#license)

  
  

## About

  

>In this project there are two jupyter notebooks namely **[from-scratch.ipynb](venv/src/from-scratch.ipynb)** and **[using-sklearn.ipynb](venv/src/using-sklearn.ipynb)**.

  

>In **from-scratch.ipynb** a `linear regression` model is built from **scratch**, using numpy for mathematical operations. This model is then trained with the data to predict Canada's GDP where Year of which we want the GDP is the input data.

  

>In **from-scratch.ipynb** `Gradient Descent`and `Normal Equation`(since the size of data is less than 10,000) are for finding the best parameters and then the model is `evaluated` using the test data.

  

>In **using-sklearn.ipynb** `sklearn` module is used the and machine learning techinques like `Cross Validation`, `Analyzing Learning Curve` and `Parameter Tunning` are used to train the model and then it is `evaluated` with the test data.

  

## Installation

  

It is highly **recommended** to use **`virtual enviroment`** for this project to avoid any issues related to dependencies.

  

Here **`pipenv`** is used for this project.

  

There is a **`requirements.txt`** file in `'Predict-GDP-of-Canada'/requirements.txt` which has all the dependencies for this project.

  

- First, start by closing the repository

  

```bash

git clone https://github.com/AkashSDas/Predict-GDP-of-Canada

```

  

- Start by installing **`pipenv`** if you don't have it

```bash

pip install pipenv

```

  

- Once installed, access the venv folder inside the project folder

```bash

cd  'Predict-GDP-of-Canada'/venv/

```

  

- Create the virtual environment

```bash

pipenv install

```

The **Pipfile** of the project must be for creating replicating project's virtual enviroment.

  

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

  

- Enable the virtual environment

```bash

pipenv shell

```

  

- dataset, jupyter notebook and model are in `'Predict-GDP-of-Canada'/requirements.txt/src` folder.

  

```bash

cd src/

```

  

- To start/view the jupyter notebook

```bash

jupyter noterbook

```

  

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.

  

## Data Source

  

The [source](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=CA) of the data used here is the World Bank national accounts data, and OECD National Accounts data files.

  

## License

  

This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
