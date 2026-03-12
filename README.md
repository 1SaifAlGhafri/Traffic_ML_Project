# Traffic Level Analysis and Prediction Machine learning Project – Abu Dhabi
This project is about understanding when traffic is low, medium, or high in Abu Dhabi and trying to predict it using code.

I created my own small dataset where each row is one hour of the day for different days (Monday, Friday, Saturday, Sunday).

The goal is to help people see when traffic is usually bad and when it is safer to go out.

# Data
I designed the data with these columns:
hour: from 0 to 23 (time of day)

day_of_week: 1 = Monday, 5 = Friday, 6 = Saturday, 7 = Sunday

is_weekend: 0 = weekday, 1 = weekend

traffic_level: 0 = low, 1 = medium, 2 = heavy

The traffic levels are based on my observations and common patterns in Abu Dhabi.

# What the code does
1)Builds a pandas DataFrame from my traffic lists.

2)Prints basic information about the data (shape, types, simple statistics).

3)Uses groupby to find average traffic by day and by hour.

4)Creates line charts and bar charts with matplotlib to show:
-Traffic during the day for each of the four days
-Average traffic level for each day
-Average traffic level for each hour (rush hours)

5)Finds the rush hour by looking for the hour with the highest average traffic.

6)Trains a DecisionTreeClassifier (machine learning model) using:
-Inputs: hour, day_of_week, is_weekend
-Output: traffic_level

7)Splits the data into training and testing sets, checks accuracy, and then predicts traffic level for a few example times.

# Use of AI and support
-I built this project while learning Python, data analysis and basic machine learning.

-I used online resources and AI assistance to help me structure the code, debug errors, and understand new functions, but I designed the dataset, chose the features, and decided what analysis and predictions to run.

-The final script is something I can explain line by line: how the data is created, how the charts are made, and how the decision tree model is trained and tested.
