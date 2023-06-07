# GaiaToCSV
Search the Gaia Database and automatically download results as a CSV file.
___
## About The Project
The Gaia mission is a European Space Agency (ESA) mission designed to archive data for over a billion stars. The Gaia Archive is freely avaible online. It's most recent data release is Gaia data release 3, and includes astrometric, photometric, and spectroscopic data. More information about the Gaia Mission and Gaia Archive can be found [here](https://www.esa.int/Science_Exploration/Space_Science/Gaia_overview).

Using the astroquery Python package one can search various astronomical databases, including Gaia, and either print results directly to the console or write the results to a file. Documentation for searching the Gaia database using astroquery can be found [here](https://astroquery.readthedocs.io/en/latest/api/astroquery.gaia.GaiaClass.html).

This project allows the user to search the Gaia Archive and export the results to a CSV file. The project uses an interface similar to Gaia, and can be easilly used without the technical knowledge needed to use either astropy or astroquery. However, knowledge of astropy and astroquery is essential to understanding the source code.
___
## Installation
This project runs in Jupyter Notebook. To use Jupyter Notebook it is necessary to download and install [Anaconda](https://www.anaconda.com/download). Once installed Jupyter Notebook can be accessed through the Anaconda Navigator.

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

These packages can installed by opening a new terminal in Jupyter Notebook and using the following command:

```pip install [Insert package name here.]```

Where the brackets are replaced with the package name. For example, to install astropy enter the command:

```pip install astropy```

___
## Instructions
To begin a search input the right acsension, declination, and radius in the corresponding entry fields at the top of the app. Units should be in degrees

Next, check the boxes for the columns to be displayed in the CSV file. For information on what data appears in each column see the [Gaia Documentation](https://gea.esac.esa.int/archive/documentation/GDR2/Gaia_archive/chap_datamodel/sec_dm_main_tables/ssec_dm_gaia_source.html).

Lastly, input a file name in the optional entry field at the bottom and click "Download CSV". This will open a dialouge box telling how much data the output file will contain. To continue click "Yes" and the file will be saved in the directory this program is saved to. This Dialogue box will close once the download is complete. To refine the search click "No" to close the dialogue box. No file will be downloaded in this case.

Note: To view this information in the app click the "Help" button in the lower left.

___
## Acknowledgements
