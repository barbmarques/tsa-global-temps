# tsa-global-temps

### ```Project Summary:```

Predict land temps of Greenland, using time series analysis modeling on a _______________ database of __________ temps ranging from 1813 to 2013. 

Dataset: 

#### ```Project Goals:```
- Create a model that will accurately predict land temperatures in Greenland for 2013.  
 
#### ```Initial Thoughts:```

- expect high correlation with sleep, stress, negative emotions, meditation 
- curious about bmi and achievement
- does high stress = high achievement / can less stress still = high achievement?
- how does female achievement compare to male
- expect higher age to contribute to higher achievement
- possibly drop flow, lost vacation, places visited, fruit_veggies, todo_completed, sufficient income


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
  
3. Run the Jupyter notebook, mode-greenland-temps, cell by cell, to reproduce my analysis.

