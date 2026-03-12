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
