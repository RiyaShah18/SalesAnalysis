# SalesAnalysis
In this project, Python Pandas and Python Matplotlib libraries have been used to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

Following business related questions have been looked upon :
1. What was the best month for sales? How much was earned that month?  
2. What city sold the most product?  
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?  
4. What products are most often sold together?  
5. What product sold the most? Why do you think it sold the most?

Data cleaning and data exploration techniques were used to answer these questions.
They include:

* Concatenating multiple csvs together to create a new DataFrame (pd.concat)
* Drop NaN values from DataFrame
* Removing rows based on a condition
* Adding columns
* Change the type of columns (to_numeric, to_datetime, astype)
* Parsing cells as strings to make new columns (.str)
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize our results
* Labeling our graphs


All monthly data is stored in the 'Data' folder. The 'annual.csv' file represents the consolidation of data from all months into a single file, achieved through the use of Pandas.


