# bike-share-data-analytics
A Python-based data analysis project that explores bike-share usage across Chicago, New York City, and Washington, DC. The project processes trip data, applies user-selected filters, and computes descriptive statistics to identify popular travel times, stations, routes, trip durations, and rider demographics.

## Project Overview

This project analyzes bike-share data from **Chicago, New York City, and Washington, DC** to uncover patterns in how people use bike-sharing systems.

Using Python, the project processes trip data from the first six months of 2017 and allows users to explore statistics based on different cities, months, and days of the week.

## Analysis Performed

The program calculates statistics for:

### Popular Times of Travel
- Most common month
- Most common day of the week
- Most common hour of the day

### Popular Stations and Trips
- Most common start station
- Most common end station
- Most frequent combination of start and end stations

### Trip Duration
- Total travel time
- Average travel time

### User Information
- Counts of each user type
- Counts of each gender for Chicago and New York City
- Earliest year of birth
- Most recent year of birth
- Most common year of birth

## Datasets

The project uses three CSV datasets:

- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`

The datasets include information such as start and end times, trip duration, stations, and user type. Chicago and New York City also include gender and birth-year information.

## Technologies Used

- Python
- Pandas
- CSV data processing
- Descriptive statistics

## Project File

The main Python program is:

`bikeshare.py`

## Purpose

The goal of this project is to practice Python programming and data analysis by loading, filtering, processing, and analyzing real-world bike-share datasets.
