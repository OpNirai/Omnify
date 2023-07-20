# Omnify
There are many tools that are available for data analytics I am going to explore the provided datasets using python.
# Google Ads Dataset and Listing site data
The Google Ads dataset consists of attributes such as week, compaign, Adgroup, Currency, Clicks, Impressions, Cost, Leads, Prospects, Payment, Payment date, Country. Listing Site dataset consists of columns such as product name, categories, Date of report, Clicks, Money Spent, Channel, Paid, Paid date.
# Q1-Create a combined report with all key metrics (esp: Spends and Returns %) in a weekly and monthly format. Decide the number of data fields you would like to showcase here.
Packages used : Pandas, Matplotlib
# Preprocessing : 
The Objective is to find the Returns and spends from the dataset. First we have to convert the NAN values in Payment and Cost column to some mathematical values which will be optimal for mathematical values. 
# Calculations :
From the payment and the cost we are going to calculate the antoher column called returns.Then from the week column in Google Ads Dataset we are going to extract the week and the month separately. Then we are going to aggregate them and we are going to provide the monthly as well as weekly report separately.
# Visualization :
For visualization of the monthly and weekly reports that we have been generated we are going to use the line plot and bar plot from the matplotlib package for visualizing the reports.
# Q2-Which is the most profitable channel
Packages used : Pandas
# preprocessing :
we have to first convert the values in the paid column to some useful mathematical value that is we have to convert the string value into numeric value for calculating the most profitable channel.
# Calculations :
We have to first find the amount spent on the individual channels for that we have used the pivot table in the dataframe for storing the data in a organized form. Similarly we are creating the pivot table for amount earned on individual channel. Then by subtracting the money earned and money spent we can come to the conclusion of our question.

