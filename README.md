# tsa-global-temps

## Climate Change: Predicting Greenland Surface Temperatures

#### ```Project Summary:```

Predict land temps of Greenland, using time series analysis modeling on a Berkeley Earth Surface Temperature Study database of  temps ranging from 1823 to 2013. 

Dataset: 

#### ```Project Goals:```
- Create a model that will accurately predict land temperatures in Greenland for 2013.  
 
 
#### ```Data Dictionary:``` 
| Attribute | Definition | Data Type |
| ----- | ----- | ----- |
|Date |starts in 1823 by month for average land temperature |datetime64|
|Average_Temp| Average land temperature in degrees Celsius |int64|
|Average_Uncertainty | the 95% confidence interval around the average temperature |int64|


#### ```Instructions for Reproducing My Findings:```
1.  Start by cloning the github repository on your From your terminal command line, enter git clone git@github.com:barbmarques/tsa-global-temps.git
2.  Ensure the following files are in your working directory:  
 - model-greenland-temps.ipynb
 - acquire.py
 - prepare.py
 - explore.py
 - GlobalLandTemperaturesByCountry.csv
  
3. Run the Jupyter notebook, mode-greenland-temps, cell by cell, to reproduce my analysis.

