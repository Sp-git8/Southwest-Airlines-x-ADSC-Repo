Results Overview:

The predicted_weather_scores.csv file is the output given from our program. This CSV file has the weather score results for all 29 airports used in our dataset. It also contains other datapoints, which include: temperature (C), percent humidity, precipitation (mm), snow (mm), and more. 

The weather score for all of these airports, calculated off of our datasets, and through our model, is in the very last column. The CSV file is alphabetically sorted by the origin airport's IATA code. 

The analysis file contains a scatter plot showing a positive correlation between airport yearly expenses and our calculated weather scores. A log function is applied to the expenses to narrow down the range of the expenses since plotting raw expenses would make smaller airports almost invisible on the scatter plot. Further, it reduces the effect of outliers. 
