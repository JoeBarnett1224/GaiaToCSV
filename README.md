# GaiaToCSV
Search the Gaia Database and automatically download results as a CSV file.

## About The Project
The Gaia mission is a European Space Agency (ESA) mission designed to archive data for over a billion stars. The Gaia Archive is freely avaible online. It's most recent data release is Gaia data release 3, and includes astrometric, photometric, and spectroscopic data. More information about the Gaia Mission and Gaia Archive can be found [here](https://www.esa.int/Science_Exploration/Space_Science/Gaia_overview).

Using the astroquery Python package one can search various astronomical databases, including Gaia, and either print results directly to the console or write the results to a file. Documentation for searching the Gaia database using astroquery can be found [here](https://astroquery.readthedocs.io/en/latest/api/astroquery.gaia.GaiaClass.html).

This project allows the user to search the Gaia Archive and export the results to a CSV file. The project uses an interface similar to Gaia, and can be easilly used without the technical knowledge needed to use either astropy or astroquery. However, knowledge of astropy and astroquery is essential to understanding the source code.

## Installation
This project runs using Jupyter Notebook. To use Jupyter Notebook it is necessary to download and install [Anaconda](https://www.anaconda.com/download). Once installed Jupyter Notebook can be accessed through the Anaconda Navigator.

In order to run the code the following packages must be installed:
- tkinter
- astroquery
- numpy
- astropy
- pyvo
- requests
- keyring
- Beautiful Soup
- html5lib
- curl
- pytest-astropy
- pytest-rerunfailures
