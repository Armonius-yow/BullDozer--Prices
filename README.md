# Predicting auction prices for Bulldozers
Predicting the auction sale price of a piece of bulldozers - for the year between 2011 and 2012.
This was a competition on Kaggle titled 'Bluebook for BullDozers'

Find data here https://www.kaggle.com/c/bluebook-for-bulldozers/data

### Description
In this project, I pursued it to teach myself how to work with Time Series data. Here I
* Parsed the date column to a datetime column in pandas
* Sort dataset by saledate
* Add separate datetime parameters (separatee column for year, month, etc

**Cleaned/Preprocessed the data by**
* Converting strings to categories
* Filling missing values (both numerical and categorical)

**Fit the data on our machine learning model**
* Test the model on a subset of the data and then took the best parameters to work with

**Built little helper functions to**
* Evaluate the metrics associated with regression ML models and our RMSLE(Root Square Mean Log error)
* Gauge feature importance with vaarious columns and plot a graph illustrating the comparisons with the columns

**As usual, the first page of the Jupyter notebook file consists of the project outline**

(I start all my projects outlining the core aspects of the project; The Problem Definition, The Data, The Evaluation standard and the Features in our dataset)
