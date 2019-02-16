# Crime Analysis with Machine Learning

A collection of crime data analysis in Jupyter Notebooks.

## Background

An organization known as the [Murder Accountability Project](http://www.murderdata.org/p/about.html) aggregated homicide data from government sources for better tracking and analysis. The data may be downloaded from [this link](http://www.murderdata.org/p/data-docs.html). The aggregated data was used in all of the Jupyter Notebooks. Economic and geographic data was sourced from the [Golden Oak Research Group](https://www.kaggle.com/goldenoakresearch/us-household-income-stats-geo-locations).


## Data Description
Categorical features were dummy encoded and information about the perpetrator was dropped. Since the perpetrator information will
not be known in unsolved cases, it could not be used for the experiments. 

The data includes information such as the department type handling the case
(state, local, county, federal), metadata about the case itself (date notified, solved status, weapon), and characteristics about the victim. 
