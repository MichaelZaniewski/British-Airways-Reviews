# British Airways Reviews | Tableau Dashboard - IN PROGRESS
![showcase](https://github.com/user-attachments/assets/04bbc344-f620-4a7e-9dd8-e367f73d5fe7)
A comprehensive analysis of customer reviews for British Airways utilizing a Tableau Dashboard.
## Background and Overview
British Airways, established in 1974, is the second largest airline in the United Kingdom. It is headquartered in London, England, with Heathrow Airport as its main hub. 

The goal of this project is to view changes in public sentiment over time utilizing numerous, filterable metrics in order to understand trends and create reccomendations that bolster consumer satisfaction in underperforming areas.  

Insights are provided on the following areas:
- The "Overall Rating" consumers report, along with average ratings in the following categories: "Cabin Staff Service," "Entertainment," "Food," "Ground Service," "Seat Comfort," and "Value for Money." 
- Sentiment changes by month, country, and aircraft per metric selected.
- Relationships between seat type and traveler type to satisfaction scores. 


## Data Structure and Info
|   column name       |     data type     |     column name     | data type           |   
|  -------------------| ------------------| ------------------- |---------------------|           
|   review_title      |    string         |       recommended   |       string        |
|       author        |       string      |     trip_verified   |    string           |
|     date            |     date          |     rating          |     integer         |
|    place            |     string        |      seat_comfort   |      integer        |     
|     content         |character varying  | cabin_staff_service |  integer            |    
|   aircraft          |     string        | food_beverages      | integer             |
| traveller_type      |       string      |  ground_service     | integer             |
|     seat_type       |       string      | value_for_money     | integer             |
|     route           |       string      | entertainment       | integer             |
| date_flown          |        date       |
## Executive Summary
THE MAIN POINT, THE MEAT, THE LARGEST MOST IMPORTANT FINDING!

- Entertainment is consistently ranked lowest. This area should be addressed immedietly as it has the most room to improve.    
### Overview of Findings
- Entertainment is consistently rated lowest amongst all other metrics, especially by those traveling in economy class.
- The Boeing 777-200 is rated highest for value in every cabin except premium economy where it's rated the lowest.
- In 2022, overall ratings from business class travelers peaked at 8.0 in February, and saw lows of 1.0 in October.
- The highest number of reviews comes from the United Kingdom at 843, followed by the United States at 128.
### Recommendations
## Assumptions, Limitations, and Caveats
### Assumptions
### Limitations
### Caveats
- Limit: Competition is not considered in these findings.

