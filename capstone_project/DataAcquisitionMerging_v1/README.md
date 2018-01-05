# Data Acquisition and Merging

This directory contains IPython notebooks that go through the data acquisition and mergind process in detail for the capstone project. There are three notebooks:

1. data_acquisition_merging.ipynb - This is the main notebook which returns the merged data file

2. history_calc.ipynb - This notebook calculates some features related with historical performances of the flights.

3. weather.ipynb - This notebook downloads weather data for a given airport location.


The main code (data_acquisition_merging.ipynb) first loads the original flight data set, then uses the output file from running history_calc.ipynb notebook. Finally, the weather data for several airport locations obtained by running weather.ipynb notebook are merged with the flight data. 
