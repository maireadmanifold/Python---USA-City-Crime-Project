# USA-City-Crime-Project
This project scraped data from various USA cities open data API portals and combined the data with USA government census information. Cities: New York, Baltimore, Chicago, Dallas, LA and San Franciso. The project was a final project for a Higher Diploma in Data Analytics from National College of Ireland (NCIRL). 
## Overview
The purpose of the project was to look at social demographics in the context of crime rates. The project results were written up as an academic paper "Greening neighbourhoods in high crime areas". Actual street tree coverage was only obtained for New York. 

Tableau was used to present map visualisation of crime and street tree geographical results. 

## API Sources
API data was scraped from following API sources: 
* USA census data: https://api.census.gov/data

* New York crime: https://data.cityofnewyork.us/Public-Safety/NYPD-Criminal-Court-Summons-Historic-/sv2w-rv3k
* Baltimore crime: https://data.baltimorecity.gov/datasets/part-1-crime-data-3/data
* Chicago crime: https ://www.chicago.gov/city/en/dataset/crime.html
* Dallas crime: https://www.dallasopendata.com/Public-Safety/Police-Incidents/qv6i-rri7
* LA crime: https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z
* San Francisco crime: https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry
## Python Prerequisities
* Import pandas
* Import numpy
* from keras.layers import Dense
* from keras.models import Sequential
* from sklearn.model_selection import train_test_split
* from sklearn.neighbors import KNeighborsClassifier
* from sklearn.preprocessing import StandardScaler
* from sklearn.decomposition import PCA
* import matplotlib.pyplot as plt
* import seaborn as sns
