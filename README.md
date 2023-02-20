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

Flights dataset metadata <br>
No Column Name Description Data type <br>
1 YEAR Year of the Flight Trip Int <br>
2 MONTH Month of the Flight Trip, Example 1 means month of January, 2 means February and so on Int <br>
3 DAY Day of the Flight Trip, Example 1 means date 1, 2 means date 2 and so on Int <br>
4 DAY_OF_WEEK Day of week of the Flight Trip, e.g. 1 represents Monday, 2 represents Tuesday and so on Int <br>
5 AIRLINE Airline Identifier String <br>
6 FLIGHT_NUMBER Flight Identifier Int <br>
7 TAIL_NUMBER Aircraft Identifier String <br>
8 ORIGIN_AIRPORT Starting Airport String <br>
9 DESTINATION_AIRPORT Destination Airport String <br>
10 SCHEDULED_DEPARTURE Planned Departure Time Int <br>
11 DEPARTURE_TIME WHEEL_OFF - TAXI_OUT Int <br>
12 DEPARTURE_DELAY Total Delay on Departure Int <br>
13 TAXI_OUT The time duration elapsed between departure from the origin airport gate and wheels off Int <br>
14 WHEELS_OFF The time point that the aircraft's wheels leave the ground Int <br>
15 SCHEDULED_TIME Planned time amount needed for the flight trip Int <br>
16 ELAPSED_TIME AIR_TIME+TAXI_IN+TAXI_OUT Int <br>
17 AIR_TIME The time duration between wheels off and wheels on time Int <br>
18 DISTANCE Distance between two airports Int <br>
19 WHEELS_ON The time point that the aircraft's wheels touch on the ground Int <br>
20 TAXI_IN The time duration elapsed between wheels-on and gate arrival at the destination airport Int <br>
21 SCHEDULED_ARRIVAL Planned arrival time Int <br>
22 ARRIVAL_TIME WHEELS_ON+TAXI_IN Int <br>
23 ARRIVAL_DELAY ARRIVAL_TIME-SCHEDULED_ARRIVAL Int <br>
24 DIVERTED Aircraft landed on airport that out of schedule Int
