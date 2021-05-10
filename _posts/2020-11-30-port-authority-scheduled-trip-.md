---
title: Port Authority Scheduled Trip Counts
created: '2020-11-30T02:50:16.157090'
modified: '2020-11-30T02:50:16.157101'
state: active
type: dataset
tags:
  - Bus
  - Picks
  - Public Transit
  - Rail
  - Schedules
  - Timetable
  - Transit
  - Transportation
  - Trip Count
  - Trip Distance
  - Trips
groups:
  - Local Government
csv_url: >-
  https://data.wprdc.org/dataset/d1eb0fcd-ba60-4407-9969-ceef464d0c00/resource/36c61dbc-9e23-4c77-9f09-ca544d3c6174/download/schedule_daily_detail.csv
json_url: ''
layout: post

---
This dataset lists Port Authority scheduled bus and rail trip counts and distances since November 2016. 

For convenience, this data is published in several formats:
- Daily Scheduled Trips: Aggregated total trip count and trip distances for each route per day.
- Monthly Scheduled Trips: Aggregated total trip count and trip distances for each route per month and day type (weekday, Saturday, and Sunday). This can be joined with the Monthly Ridership dataset on DateKey, Route, and DayType to normalize the average riders per trip.
- Detailed Daily Scheduled Trips: This dataset lists the detailed daily schedule for each route, including the start and end times for each trip. This can be used to see the earliest and latest runs and study peak- and off-peak trip frequencies.

Port Authority makes quarterly schedule adjustments that include adding and removing trips on certain routes to better serve riders.  These schedule adjustments are called "picks" and correspond to the year and month of the schedule change, e.g. the November 2016 pick is known as 1611.
