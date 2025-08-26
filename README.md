Weather Data Management System

Project Overview

This project is developed to fetch and store real-time weather data
using the Open-Meteo API. The system is implemented in Zoho Creator and
automates the process of retrieving temperature, latitude, longitude,
and time data for selected cities.

Features

-   City selection via dropdown (Istanbul, Ankara, Balikesir)
-   Automatic assignment of latitude and longitude
-   Fetching current weather and hourly backup data from Open-Meteo API
-   Storing results in the Weather form

Workflow Script (Form Action)

-   User selects a city (dropdown)
-   Latitude and Longitude fields are automatically filled
-   Real-time weather data fetched from Open-Meteo API
-   Temperature and Hour fields updated accordingly

Scheduled Script (Automation)

-   Runs periodically to update all city weather records
-   Fetches weather data for each stored city
-   Inserts latest temperature and time into Weather form

Technologies Used

-   Zoho Creator (Deluge Script, Forms, Workflow, Scheduler)
-   Open-Meteo API (for real-time weather data)

Future Improvements

-   Add more cities dynamically
-   Store historical weather trends
-   Visualize data using charts inside Zoho Creator
