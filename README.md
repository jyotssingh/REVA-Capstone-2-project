# REVA-Capstone-2-project: Flight delay prediction for Indian air carriers with Explainable Artificial Intelligence

The primary goal of the project is to forecast flight delays for the selected airports and airlines. 
The important element of the business objective is also to identify the primary causes of delay for a specific airline and/or airport with significant delays using Explainable AI.

Five airports and six carriers were chosen to explore the factors influencing flight scheduling and delays specifically on these particular routes. The rationale behind this was that the five airports chosen - Delhi, Mumbai, Bangalore, Hyderabad, and Kolkata - contributed more than half of all domestic passenger flow. There is a considerable likelihood of flight delays at the busiest airports. The country's geographical diversity is also reflected in these airports' locations. As a result, a study of the flight schedules from these airports will typically reflect the characteristics of the population data.

Indigo, Air India, SpiceJet, GoAir, Air Asia, and Vistara; the six airlines under consideration, collectively control 99.4% of the domestic market.

The flight information dataset consists of **14951 observations and 22 features** during a period of two years, from January 2018 to January 2020. The weather dataset includes **14 meteorological features and 90600 observations** spread throughout two years, from January 2018 to January 2020.

Below are the features categorized based on their type:

**1.	Airport scores (Departure and Arrival)** – The Airports Authority of India (AAI), is a legal body, under the ownership of the Ministry of Civil Aviation, Government of India. The AAI is in charge of issuing rankings for all Indian airports according to predetermined standards.

a.	Airport Rating – Overall rating of the airport based on the operations, management, and development of the airport

b.	Airport On-Time Rating – Airport performance based on the aircraft arrival at the gate under 15 minutes of the scheduled arrival time

c.	Airport Service Rating - Ratings from the customer reviews, which take into account the cleanliness of the airport, wait times, airport shopping, cafes and restaurants, wifi availability, and staff services

**2.	Airline Ratings**

a.	Carrier Rating – Based on the quality of the airline's overall services

b.	Carrier Market Share – Airline market share based on their market position, Revenue generation, and the Operating Cost structure

c.	Carrier Load Factor – Measures the proportion of seats that have been occupied by passengers. A high load factor implies that an airline has sold the majority of its available seats, and is favored over a low load factor.

d.	Carrier On-Time Performance rating - Performance of the carrier as measured by the aircraft arriving at the gate within 15 minutes of the planned arrival time


**3.	Flight Departure and Arrival details**

a.	Departure and Arrival Airports

b.	Scheduled Departure and Arrival time

c.	Duration of the flight

d.	Actual Departure and Arrival time


**4.	Weather details (Departure and Arrival Airport)**

a.	Dew Point

b.	Wind Gust, Wind Speed, and Wind direction 

c.	Cloud Cover

d.	Humidity and Precipitation

e.	Pressure and Temperature

f.	Visibility

**The .ipynb file comprises of Data pre-processing, EDA, Model building using Supervised ML algorithms (Linear Regression, MLPRegressor) and the Expalainable AI using LIME**
