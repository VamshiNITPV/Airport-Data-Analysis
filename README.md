# Indigo Flight - Data Analysis
This project performs an in-depth analysis of airport traffic data to uncover trends in passenger movements, freight, and mail across cities and time periods. Using SQL, it explores metrics like busiest airports, top routes, and correlations with city populations, based on the Airport_Project_Data.csv dataset. The project is designed for researchers, data analysts, and aviation enthusiasts to derive actionable insights from flight data.
# 🗃️ Dataset Description





File: Airport_Project_Data.csv



Columns (36 total):





PASSENGERS: Number of passengers (numeric).



FREIGHT: Freight weight in pounds (numeric).



MAIL: Mail weight in pounds (numeric).



DISTANCE: Flight distance in miles (numeric).



UNIQUE_CARRIER: Unique carrier code (e.g., "AA").



AIRLINE_ID: Numeric airline identifier.



UNIQUE_CARRIER_NAME: Full carrier name (e.g., "American Airlines").



UNIQUE_CARRIER_ENTITY: Carrier entity code.



REGION: Region code (e.g., "D" for domestic).



CARRIER: Carrier code.



CARRIER_NAME: Full carrier name.



CARRIER_GROUP, CARRIER_GROUP_NEW: Carrier group identifiers (numeric).



ORIGIN_AIRPORT_ID, ORIGIN_AIRPORT_SEQ_ID, ORIGIN_CITY_MARKET_ID: Origin airport and city identifiers (numeric).



ORIGIN: Origin airport code (e.g., "JFK").



ORIGIN_CITY_NAME: Origin city (e.g., "New York, NY").



ORIGIN_STATE_ABR, ORIGIN_STATE_FIPS, ORIGIN_STATE_NM, ORIGIN_WAC: Origin state and world area code details.



DEST_AIRPORT_ID, DEST_AIRPORT_SEQ_ID, DEST_CITY_MARKET_ID: Destination airport and city identifiers (numeric).



DEST: Destination airport code (e.g., "LAX").



DEST_CITY_NAME: Destination city (e.g., "Los Angeles, CA").



DEST_STATE_ABR, DEST_STATE_FIPS, DEST_STATE_NM, DEST_WAC: Destination state and world area code details.



YEAR, QUARTER, MONTH: Time period of the flight (numeric).



DISTANCE_GROUP: Distance category (numeric).



CLASS: Service class (e.g., "F" for first class).

# 🛠️ Prerequisites





MySQL: Version 8.0+ (e.g., MySQL Community Server).



MySQL Workbench: For running queries and importing data.



Git: To clone the repository.



Python (optional): For generating INSERT statements if needed.



Dataset: Airport_Project_Data.csv (included in the repository or provided separately).
