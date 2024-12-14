# BAA5063-Grp-Assignment
# Flight Delay and Cancellation Dataset (2019-2023)

## Dataset Description
**Dimensions:** 3,000,000 rows and 32 columns  
**File Format:** CSV  
**File Size:** 599,747 KB
**Source/Link:** [https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023]

## Data Dictionary

| Variable                | Type        | Description                                                                            |
|-------------------------|-------------|----------------------------------------------------------------------------------------|
| FL_DATE                 | Date        | The date of the flight.                                                                |
| AIRLINE                 | Categorical | The airline operating the flight.                                                      |
| AIRLINE_DOT             | Categorical | DOT airline code (for regulatory purposes).                                            |
| AIRLINE_CODE            | Categorical | Airline code (e.g., "AA" for American Airlines, "DL" for Delta).                       |
| DOT_CODE                | Categorical | DOT carrier code.                                                                      |
| FL_NUMBER               | Integer     | The unique flight number.                                                              |
| ORIGIN                  | Categorical | The code of the origin airport.                                                        |
| ORIGIN_CITY             | Categorical | The city corresponding to the origin airport.                                          |
| DEST                    | Categorical | The code of the destination airport.                                                   |
| DEST_CITY               | Categorical | The city corresponding to the destination airport.                                     |
| CRS_DEP_TIME            | Integer     | Scheduled departure time (local time).                                                 |
| DEP_TIME                | Integer     | Actual departure time.                                                                 |
| DEP_DELAY               | Numeric     | Departure delay in minutes.                                                            |
| TAXI_OUT                | Numeric     | Time in minutes from pushback to takeoff.                                              |
| WHEELS_OFF              | Integer     | Actual time when the aircraft took off.                                                |
| WHEELS_ON               | Integer     | Actual time when the aircraft landed.                                                  |
| TAXI_IN                 | Numeric     | Time in minutes from landing to gate arrival.                                          |
| CRS_ARR_TIME            | Integer     | Scheduled arrival time (local time).                                                   |
| ARR_TIME                | Integer     | Actual arrival time.                                                                   |
| ARR_DELAY               | Numeric     | Arrival delay in minutes.                                                              |
| CANCELLED               | Binary      | 1 if the flight was cancelled, 0 if not.                                               |
| CANCELLED_CODE          | Categorical | Reason for cancellation (A: Carrier, B: Weather, C: National Air System, D: Security). |
| DIVERTED                | Binary      | 1 if the flight was diverted, 0 if not.                                                |
| CRS_ELAPSED_TIME        | Numeric     | Scheduled flight duration in minutes.                                                  |
| ELAPSED_TIME            | Numeric     | Actual flight duration in minutes.                                                     |
| AIR_TIME                | Numeric     | Time spent in the air in minutes.                                                      |
| DISTANCE                | Numeric     | Flight distance between origin and destination airports (in miles).                    |
| DELAY_DUE_CARRIER       | Numeric     | Delay caused by the carrier (in minutes).                                              |
| DELAY_DUE_WEATHER       | Numeric     | Delay caused by weather (in minutes).                                                  |
| DELAY_DUE_NAS           | Numeric     | Delay caused by National Aviation System (NAS) issues (in minutes).                    |
| DELAY_DUE_SECURITY      | Numeric     | Delay caused by security-related issues (in minutes).                                  |
| DELAY_DUE_LATE_AIRCRAFT | Numeric     | Delay caused by a late-arriving aircraft (in minutes).                                 |

*End of Table*

---
