# Exploratory-Data-Analysis-using-python
Exploratory data analysis (EDA) is one of the core components of data science. This repository demonstrates some common exploratory data analysis methods and techniques using python.  
Two datasets of Covid-19 taken from Kaggle are analyzed. Through the analysis, we uncovered the answers of many interesting questions and get more insights on the dynamics of the pandemics.
## DataSet Overview
The dataset is taken from kaggle and contains details of the used cars in germany which are on sale on ebay.
The dataset is not clean and hence a lot of data cleaning is carried out. For e.g. prices where too high which are replaced by the median and outliers are removed accordingly.
Also vehicles whose registration year was greater than 2016 and less than 1890 were removed from the dataset as this data is inconsistense and would yield incorrect results.
The dataset is cleaned and stored in a CleanData folder which contains the entire cleaned dataset named as cleaned_autos.csv and another folder named DataForAnalysis containing files structures containing subsets of the cleaned dataset based on brand of the vehicles and vehicle types.
