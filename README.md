# Flight-Operations-Analytics-Optimizing-Airline-Performance-Excel

Link:- https://docs.google.com/spreadsheets/d/1VPhROOtvc-utVhLIXm_Ll4fU9d6y9Vmb/edit?usp=sharing&ouid=108839445152779777461&rtpof=true&sd=true

**Problem statement:-**
The primary objective of this case study, titled "Sky Analytics: Navigating the Complexities of Airline and Airport Operations," is to deeply analyse and interpret the extensive datasets encompassing flights, airlines, and airports - namely "flights.csv", "airlines.csv", and "airports.csv". The analysis aims to uncover critical insights into flight operations, delay patterns, airline efficiency, and airport traffic dynamics. By exploring these datasets, the study seeks to identify key factors influencing operational efficiency, understand the intricacies of flight scheduling and delays, and evaluate the performance metrics of airlines and airports. The ultimate goal is to provide strategic recommendations to enhance operational effectiveness, improve customer experiences in air travel, and contribute to the overall advancement of the aviation industry's standards and practices.  

**Data Source:-**
1.	Flights Dataset  
flights.csv  
This dataset contains detailed flight information, including timings, delays, and other flight-specific data.  
•	YEAR, MONTH, DAY, DAY_OF_WEEK: Date and day information for the flight.  
•	AIRLINE: Airline identifier.  
•	FLIGHT_NUMBER: Flight number.  
•	TAIL_NUMBER: Aircraft tail number.  
•	ORIGIN_AIRPORT, DESTINATION_AIRPORT: Airport codes for origin and destination.  
•	SCHEDULED_DEPARTURE, DEPARTURE_TIME: Scheduled and actual departure times.  
•	DEPARTURE_DELAY: Delay in departure (minutes).  
•	TAXI_OUT: The time duration between departure from the gate and wheels off.  
•	WHEELS_OFF, WHEELS_ON: Time when wheels were off/on the ground.  
•	SCHEDULED_TIME: Scheduled duration of the flight.  
•	ELAPSED_TIME: Actual time taken for the flight.  
•	AIR_TIME: Time in the air.  
•	DISTANCE: Distance covered by the flight.  
•	TAXI_IN: The time duration from wheels on to arrival at the gate.  
•	SCHEDULED_ARRIVAL, ARRIVAL_TIME: Scheduled and actual arrival times.  
•	ARRIVAL_DELAY: Delay in arrival (minutes).  
•	DIVERTED, CANCELLED: Indicators for diverted or cancelled flights.  
•	CANCELLATION_REASON: Reason for cancellation (if any).  
•	AIR_SYSTEM_DELAY, SECURITY_DELAY, AIRLINE_DELAY, LATE_AIRCRAFT_DELAY, WEATHER_DELAY: Different types of delays (minutes).  
1.	Airlines Dataset  
airlines.csv  
This dataset provides information about various airlines.  
•	IATA_CODE: Unique airline code.  
•	AIRLINE: Full name of the airline.  

1.	Airports Dataset
airports.csv
This dataset contains information about various airports.  
•	IATA_CODE: Unique airport code.  
•	AIRPORT: Full name of the airport.  
•	CITY: City where the airport is located.  
•	STATE: State where the airport is located.  
•	COUNTRY: Country where the airport is located.  
•	LATITUDE, LONGITUDE: Geographic coordinates of the airport  


**Approach: -** 
1.	Import and data per processing: -
Imported all 3 data set, checked and removed any duplicates and null values. Merged all three datasets over common columns.  

2.	New column creation: -
Created additional columns like time slot, Major delay reason, whether flight is delayed or not using existing data.  

3.	Data summarization:-
Created various pivot table to summarize the data.  

4.	Visualization: -
Plotted various chats to visualize raw data and pivot table.  

5.	Dashboard Creation: -
Created Dashboards to provide summarized view of all important charts. Added slicer to make it more interactive and insightful.  


![Image 1](https://drive.google.com/uc?id=1hSLPUUYnM60YnD_dlF8P3QAEhbBOCUEe)
![Image 2](https://drive.google.com/uc?id=1gBseSJ_KyGozbogbdhSVEoUffkwAjn2I)




**Key Insights: -**

1.	Top 5 airports handle almost 50% of all traffic.   
2.	Almost all airlines are only around 50% on time.  
3.	Early week and end of the week has highest number of cancellation and delayed flights.  
4.	Late aircraft delay and airline dealer aunty two most prominent reason of delay.  
5.	Morning and afternoon times a lot has a higher number of flights, and delay, on contrary, night has 20 number of flights and very less number of delays.  

**Conclusion: -** 
In this project we have done analysis of extensive data set consisting data from flight, airlines and airports using Microsoft Excel and tried to uncover insights and patterns 
Started with importing data cleaning data merging data and creating additional column 
Various charts and graph and finally created dashboard 
This will help airport airlines other related entries to better understand and optimise their operations and do future planning
