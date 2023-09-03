# Objectives
The main objectives of the project are as follows:
1. Explore crime rate in India.
2. Detection of patterns among unrelated data attributes by
implementing a basic model using Multiple Linear regression.
3. Implement novel visualization techniques for interactive
visualization.
4. Analyze the results.
   
# Data Description
Data used in this project is a combination of features extracted from 5
individual datasets. The data for literacy rates as well as population rates of
each state was scraped from the 15th official census calculation conducted in
2011. The web interface of Census2011 presents all the data in table format.
Data for poverty rates is based on Tendulkar poverty estimation and was
appropriated from the official website of data.gov.in ( https://data.gov.in/ ).
The data for unemployment rates of each state in India was scraped from the
NSSO (National Sample Survey Office) report for unemployment released by
the Ministry of Statistics and programme implementation. The crime dataset
was sourced from NRCB website. The final dataset used contained the features
Literacy Rate, Unemployment Rate, Poverty Rate and Crime Rate for each
state in India.

# Installing Plotly for interactive graphs
Firsly install cufflinks
```
pip install cufflinks
```
**or**
through conda terminal (To open conda terminal open Start menu and type anaconda prompt)
```
conda install -c conda-forge cufflinks-py
```
plotly.py may be installed using pip...
```
pip install plotly
```
**or** through conda terminal
```
conda install -c plotly plotly=4.6.0
```
