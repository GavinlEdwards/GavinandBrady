# Gavin and Brady csci1070_final project
Our goal of this project is to see if we can 'accurately' predict the change in stock values based off a number of variables. <br>
 We're using the stocks previous opening, closing, highs, and lows to predict future performance.
We have 2 datasets we use, one as training data and one as the actual test data. We started by cleaning the data. The data was fairly clean so it took minimal cleaning.
We dropped a few columns but also changed the date column and turned it into 4 columns: days since a reference date(the earliest date in our set)years, months, and days to see 
if there might be any correlation there. <br>
We then performed a few methods of machine learning to create confusion matrices and see which one gives us the highest precision.
We performed KNN, XGB, and rf. These models provided similiar outcomes however XGB was the best at a 70% precision.
