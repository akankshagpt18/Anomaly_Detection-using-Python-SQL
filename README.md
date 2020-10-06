# Anomaly_Detection-using-Python
First project is on Geo-spatial data where I am extracting the data using SQLite and then performing data exploratory analysis on the data. I have also performed on data visualisation to understand the data.


Second Project is on finding anomaly using Isolation forest. I am trying to aggregate the data by load_date to get count of rows per load_date and then applying Isolation forest to fetch anomaly. I am wrapping the Isolation Forest Model in a function so that we can also create a module out of it so that we can apply it on any other data in the same format

Anomaly_detection_SQL: This file has SQL template for statistical models that can be used to detect anomaly in the data
Methods: Standard Deviation, Median Absolute Deviation, Double MAD, Modified Z-score and Tukey's method  
