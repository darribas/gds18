# Software

---

| <CENTER>OS</CENTER>    | | <CENTER>Status</CENTER> |
| ------- | ----- | -----------------|
| Linux & macOS  | | [![Build Status](https://travis-ci.org/darribas/gds17.svg?branch=master)](https://travis-ci.org/darribas/gds17) |
| Windows |  | [![Build status](https://ci.appveyor.com/api/projects/status/ffyxalxow6jcs12u?svg=true)](https://ci.appveyor.com/project/darribas/gds17) |

---

This course is best followed if you can reproduce the examples and tutorials provided with it. To do so, you will need to install in your machine a series of software packages. These are all open-source and available for free to download. Although there are several ways to approach this process, we first enumerate here the list of dependencies and then show two simple approaches to install them in different platforms.

## Complementary material to this guide

This guide assumes you have the following additional files, available to download by clicking (to download them, right click on the link and select the "save as" option):

* [`install_gds_stack.yml`](content/infrastructure/install_gds_stack.yml)
* [`check_gds_stack.ipynb`](content/infrastructure/check_gds_stack.ipynb)

## Installation

### Anaconda

The easiest way to install locally and natively the software stack required is to install a full scientific Python distribution. Although other good alternatives are also available (e.g. [Canopy](https://www.enthought.com/products/canopy/), [Sage](http://www.sagemath.org)), we recommend to install [Anaconda](https://store.continuum.io/cshop/anaconda/). Make sure, whichever option you pick, to install a **Python 3.5** version, NOT Python 2. Please follow the instructions provided in the link for installation.

Once you have a fully working Anaconda distribution installed in your computer, you can setup an isolated environment that contains all the required libraries by running the install script provided with this guide. Exact instructions vary depending on the platform you are on. 

#### macOS/Linux

Open up a terminal ("Applications --> Utilities --> Terminal" in macOS and  "ctr+alt+T" in Linux) and run the following commands:

* Navigate to the folder where this file is (e.g. Downloads):

    ```
    cd /path/to/folder/
    ```

* Execute the following command:

    ```
    conda-env create -f install_gds_stack.yml
    ```

* Once this has run, you should be able to activate the environment:

    ```
    source activate gds
    ```

#### Windows

Open up the Anaconda Command Prompt (search for it on the Startup Menu) and run the following commands:

* Navigate to the folder where this file is (e.g. Downloads):

    ```
    cd /path/to/folder/
    ```

* Execute the following command:

    ```
    conda-env create -f install_gds_stack.yml
    ```

* Once this has run, you should be able to activate the environment:

    ```
    activate gds
    ```


## Check

To check things have installed correctly, an additional file is included, `check_gds_stack.ipynb`. To run the check, open a terminal (macOS/Linux) or the Anaconda Command Prompt (Windows), navigate to the folder as showed above and activate the environment:

* macOS/Linux:

    ```
    source activate gds
    ```

* Windows:

    ```
    activate gds
    ```

You should now see `(gds)` on the beginning of the line at the terminal/command prompt. You can now run the test as:

`jupyter nbconvert --execute check_gds_stack.ipynb`

This will run and, when finished, produce an HTML file in the same folder. Open it and check there are no errors reported. If that is the case, you are good to go!

## Dependencies

The course requires the following libraries to be installed on your machine. The guide above provides instructions to install them satisfactory but, in case you want to install them separately on your own (recommended only if you know what you're doing), this is the list:

* [`IPython`](http://ipython.org) 
* [`Jupyter`](https://jupyter.org)
* [Python 3.5](https://www.python.org)

---

* [`bokeh`](http://bokeh.pydata.org/en/latest/)
* [`matplotlib`](http://matplotlib.org)
* [`mplleaflet`](https://github.com/jwass/mplleaflet)
* [`seaborn`](http://stanford.edu/~mwaskom/software/seaborn/)

---

* [`qgrid`](https://github.com/quantopian/qgrid)
* [`pandas`](http://pandas.pydata.org)
* [`scikit-learn`](http://scikit-learn.org/stable/index.html)
* [`statsmodels`](http://www.statsmodels.org/stable/index.html)
* [`xlrd`](https://pypi.python.org/pypi/xlrd)
* [`xlsxwriter`](https://xlsxwriter.readthedocs.io)

---

* [`geopandas`](http://geopandas.org)
* [`PySAL`](http://pysal.org)
* [`rasterio`](https://pypi.python.org/pypi/rasterio/)


