**Flight Price Prediction** </br>
**Project Overview** </br>
This project aims to analyze and predict flight ticket prices based on various features related to flight journeys. The dataset includes information on airlines, journey dates, sources, destinations, routes, departure and arrival times, durations, stops, and additional information such as meal options or layovers. The primary goal is to explore the data (EDA) and prepare it for building machine learning models to accurately predict flight prices.

**Dataset Description** </br>
The dataset contains information on approximately 10,683 flight records with the following columns:

Airline: Name of the airline operating the flight (e.g., IndiGo, Air India, Jet Airways)

Date_of_Journey: Date of the flight journey

Source: Source city of the flight

Destination: Destination city of the flight

Route: Flight route including stops

Dep_Time: Departure time

Arrival_Time: Arrival time

Duration: Flight duration in hours and minutes

Total_Stops: Number of stops during the flight (e.g., non-stop, 1 stop, 2 stops)

Additional_Info: Extra information such as meal availability, layovers, or baggage details

Price: Ticket price (target variable)

Additional processed features in the analysis include date, month, year, arrival and departure hour and minute extracted for modeling.

**Exploratory Data Analysis (EDA)** </br>
Analysis of distribution of flight prices across different airlines and routes.

Impact of journey date, month, and temporal variables on price variation.

Influence of factors such as number of stops, duration, and additional info on pricing.

Data cleaning steps including handling missing values and feature engineering for model readiness.

**Environment Setup** </br>
Ensure the following libraries are installed: </br>

pandas </br>
numpy </br>
matplotlib </br>
seaborn </br>
openpyxl (for reading Excel files) </br>
