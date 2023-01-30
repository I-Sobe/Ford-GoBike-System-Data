# Ford GoBike System Dataset
## by Nwangene Sobe-Olisa
### a Udacity-ALX Data Visualization Project

## Dataset

> The dataset consists of data about 183,412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains features like ride durations, riders gender, start and end time of ride, customer type and other variables. The dataset can be downloaded [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv/).

## Environment
This project was written in python using Anaconda's jupyter notebook. The following following packages needs to be installed in other to effectively run:
* numpy
* pandas
* matplotlib.pyplot
* seaborn
* datetime

## Context
> For this visualization project, i wrangled the data to remove null values and extract variables like; start and end hour, start and end day and riders age group from the already existing variables in the dataset.
> The main feature of interest is the riders duration (duration_sec) column. 

## Summary of Findings

>During the exploration stage, on analyzing the mean duration of rides is 600secs and majority (mode) of the trips was on thursday and tuesday while saturday and sundays had the less number of trips. Also, a look at the busiest hour showed that 8th and 9th hour in the morning and 17th to 18th hour in the evening saw the highest volume of rides. This ride data coincides to the morning and evening rush hours and also the low amount of rides on weekends could be explain as a result of limited office hours on weekends. A further analysis showed that weekend rides are on the average longer than the rest of the week while rides around 2nd and 3rd hour are on the average longer than other hours of the day. 

> Moving forward, my analysis shows that most of the riders are male millenials (18-37) that are subscribed to the service and don't share rides. 

> Summarily, on the average the longest rides are made on weekends by 'other gender' riders especially those within the Gen Z age bracket.

## Key Insights for Presentation

> For the prsentation, i focus on the frequencies of rides per hour, day, gender, age and user type. Finally checking out average trip duration with respect to ride hour, day, gender and age.