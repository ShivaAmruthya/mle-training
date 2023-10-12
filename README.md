# Project Description
# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## Command to create an environment from the env.yml file you have generated
'''python
conda env create -n mle-dev -f env.yml
'''

## Command to activate the environment
'''python
conda activate mle-dev
'''

## Command to execute the script
'''python
python nonstandardcode.py
'''
