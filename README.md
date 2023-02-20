# Flight-delays
Data analysis of flight delays and cancellations in the USA in 2015

The flight-delays prediction dataset has become one popular dataset used by the aviation
industry to predict the delay given the historical flight data. Learning from data can be
beneficial for the companies, e.g. aviation industry, so that they can minimize the delay to
improve customer satisfaction. The insight of the data can be obtained by conducting some
steps, including pre-processing, visualization, and data modelling.

Information on Dataset
The flight-delays and cancellation data was collected and published by the U.S. Department
of Transportation’s (DOT) Bureau of Transportation Statistics. This data records the flights
operated by large air carriers and tracks the on-time performance of domestic flights. This
data summarises various flight information such as the number of on-time, delayed, cancelled,
and diverted flights published in DOT's monthly in 2015.

Flights dataset metadata
No Column Name Description Data type
1 YEAR Year of the Flight Trip Int
2 MONTH Month of the Flight Trip, Example 1 means month of January, 2 means February and so on Int
3 DAY Day of the Flight Trip, Example 1 means date 1, 2 means date 2 and so on Int
4 DAY_OF_WEEK Day of week of the Flight Trip, e.g. 1 represents Monday, 2 represents Tuesday and so on Int
5 AIRLINE Airline Identifier String
6 FLIGHT_NUMBER Flight Identifier Int
7 TAIL_NUMBER Aircraft Identifier String
8 ORIGIN_AIRPORT Starting Airport String
9 DESTINATION_AIRPORT Destination Airport String
10 SCHEDULED_DEPARTURE Planned Departure Time Int
11 DEPARTURE_TIME WHEEL_OFF - TAXI_OUT Int
12 DEPARTURE_DELAY Total Delay on Departure Int
13 TAXI_OUT The time duration elapsed between departure from the origin airport gate and wheels off Int
14 WHEELS_OFF The time point that the aircraft's wheels leave the ground Int
15 SCHEDULED_TIME Planned time amount needed for the flight trip Int
16 ELAPSED_TIME AIR_TIME+TAXI_IN+TAXI_OUT Int
17 AIR_TIME The time duration between wheels off and wheels on time Int
18 DISTANCE Distance between two airports Int
19 WHEELS_ON The time point that the aircraft's wheels touch on the ground Int
20 TAXI_IN The time duration elapsed between wheels-on and gate arrival at the destination airport Int
21 SCHEDULED_ARRIVAL Planned arrival time Int
22 ARRIVAL_TIME WHEELS_ON+TAXI_IN Int
23 ARRIVAL_DELAY ARRIVAL_TIME-SCHEDULED_ARRIVAL Int
24 DIVERTED Aircraft landed on airport that out of schedule Int
