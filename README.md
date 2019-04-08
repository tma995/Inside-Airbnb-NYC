# Inside-Airbnb-NYC

## Overview

Analyzing dataset for Airbnb listings in New York City as of `2019-03-06`, finding insights and publish [Data Science Blog](https://medium.com/@tma995/3-tips-of-booking-nyc-airbnb-homes-for-solo-adventurers-10782392e12f).

## Table of Contents

1. [Installations](#Installations)
2. [Project Motivation](#Motivation)
3. [File Descriptions](#File)
4. [Instructions](#Instructions)
5. [Licensing, Authors, Acknowledgements](#Licensing)

## Installations<a name="Installations"></a>

Python 3 environment with following libraries:

* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`
* `plotly`
* `xgboost`
* `shap`

## Project Motivation<a name="Motivation"></a>

In this project, I am interested in finding insights from Airbnb dataset in New York City. Three main questions for me to start with are below:

* What are the differences of Airbnb Homes between boroughs of New York?
* How much time in advance is best to book an Airbnb before going to NYC?
* What are the key features that affects NYC Airbnb prices?

## File Descriptions<a name="File"></a>

Following files are included in this directory:

    .
    ├── README.md    
    ├── Inside Airbnb NYC.ipynb                       # Jupyter Notebook for all process
    └── Inside Airbnb NYC.html                        # HTML page of notebook
        
## Instructions<a name="Instructions"></a>

Data files are not included in this repo, all of which can be downloaded under section **New York City** from [here](http://insideairbnb.com/get-the-data.html). 

To run the Notebook, following downloaded data files need to be put under home directory:

|Date Compiled|City|File Name|Description|
| ------ | ------ | ------ | ------ |
|2019-03-06|New York City|listings.csv.gz|Detailed Listings data for New York City|
|2019-03-06|New York City|calendar.csv.gz|Detailed Calendar Data for listings in New York City|
|N/A|New York City|neighbourhoods.geojson|GeoJSON file of neighbourhoods of the city.|

The main findings of the code can be found at my [medium blog post](https://medium.com/@tma995/3-tips-of-booking-nyc-airbnb-homes-for-solo-adventurers-10782392e12f).

## Licensing, Authors, Acknowledgements<a name="Licensing"></a>

Must give credit to **Inside Airbnb** for the data. All data was retrieved from <http://insideairbnb.com/get-the-data.html>.
