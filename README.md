# Data-Preprocessing_R

## Data Pre-Processing for World Population dynamics Data-set

The data sets used in this exercise contain world population evolution (from 1960 to 2017) and countries income classification for 264 observations. Firstly, the variables in the data sets have been carefully examined in order to get a proper understanding on the data sets. The two data sets have been merged using the common variable of Country Code. Then, the structure and attributes of the merged data set have been carefully checked. Data types of a few variables have been converted to have a better representation of the data. In order to make the data set tidier, unnecessary variables for the exercise have been dropped. Also a few variables have been relabeled to have a better representation. After that, the data set have been transformed from wide format to long format. Subsequently, the missing values and special values in the data set have been appropriately treated. The outliers of the data set have been investigated using the z-score method. The numerical variable of “Total_population” has been checked for its distribution using Histogram and identified that its not normal, but strongly right-skewed. By using logarithm base e (ln) transformation, this variable has been converted to normally distributed representation for convenient analysis.


## Data Sourse: 
https://data.worldbank.org/indicator/SP.POP.TOTL

## R codes: 
MATH2349_1850_Assignment_3_submission.rmd

## Data-sets folder: 
Contains data-sets used for the project

## Report: 
MATH2349_1850 Assignment 3_s3400652.pdf
