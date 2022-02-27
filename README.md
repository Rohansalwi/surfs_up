# Surf's Up
Surf's Up with Advanced Data Storage and Retrieval

## Purpose
Explain the structures, interactions, and types of data of a provided dataset.
Differentiate between SQLite and PostgreSQL databases.
Use SQLAlchemy to connect to and query a SQLite database.
Use statistics like minimum, maximum, and average to analyze data.
Design a Flask application using data.

## Overview:
An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern is the precipitation forcing the shop to close too frequently. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

## Results:
### June Statistics for the Temperature.
<img width="141" alt="Screen Shot 2022-02-24 at 4 58 01 PM" src="https://user-images.githubusercontent.com/96554223/155614527-243f8d35-615f-4e6c-bd24-2c495d6ccd23.png">


### December Statistics for the Temperature
<img width="175" alt="Screen Shot 2022-02-24 at 4 56 52 PM" src="https://user-images.githubusercontent.com/96554223/155614407-a5df7097-94ab-4802-b6b3-fb99d6b4eb30.png">

The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December.

## Summary:
The investor's main concern was getting rained out too frequently. Comparing the June and December weather patterns, the temperature means are reasonably close. The temperature data is not strongly skewed for either month. The data along with precipitation details supports opening a Surf and Ice Cream shop year-round. In addition to temperatures, we also included the precipitation data for June and Dec as follows.

<img width="135" alt="Screen Shot 2022-02-27 at 5 36 14 PM" src="https://user-images.githubusercontent.com/96554223/155902933-e8675a12-9ead-4943-8270-a371396f0974.png">
<img width="133" alt="Screen Shot 2022-02-27 at 5 36 30 PM" src="https://user-images.githubusercontent.com/96554223/155902936-ddcbc359-c2d1-4136-b9d6-733e2a6bd278.png">

Looking at bot the temperature and precipitation data, we can safely conclude to have the store open year round.
