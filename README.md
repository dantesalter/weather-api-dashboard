# US State Capital Weather Analysis

A data analytics project that retrieves live weather data for all 50 U.S. state capitals using the Open-Meteo API, processes the data with Python and Pandas, and visualizes the results in Power BI.

## Technologies Used

- Python
- Pandas
- Requests
- REST API
- Power BI

## Project Workflow

API → Python → JSON → Pandas → CSV → Power BI Dashboard

## Objective

Analyze current weather conditions across all U.S. state capitals and identify temperature and wind trends through interactive visualizations.

## Data Collection

Weather data was collected from the Open-Meteo API using latitude and longitude coordinates for each state capital.

Data retrieved:

- Temperature
- Wind Speed
- State
- Capital City

## Data Processing

The Python script:

1. Loops through all 50 state capitals
2. Sends API requests
3. Parses JSON responses
4. Extracts weather metrics
5. Stores results in a Pandas DataFrame
6. Exports the cleaned dataset to CSV


## Dashboard Preview

![Dashboard Overview](<img width="1421" height="800" alt="Screenshot 2026-06-02 151127" src="https://github.com/user-attachments/assets/d07e0762-f595-4151-b0f2-087f55d16842" />
)

## Key Findings

- Weather data collected for all 50 state capitals
- Interactive geographic visualization of weather patterns
- Comparative temperature analysis across states
- Wind speed analysis across state capitals


## Future Improvements

- Automate daily data refreshes
- Store historical weather data
- Create trend analysis dashboards
- Deploy automated reporting pipeline
