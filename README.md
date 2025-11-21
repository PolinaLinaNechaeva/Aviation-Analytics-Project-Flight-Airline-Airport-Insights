✈️ Aviation Analytics Project - Flight, Airline & Airport Insights

Full End-to-End Data Analysis · KPI · Geo · Tableau Dashboard

⸻

📌 Overview

This project analyzes airlines, airports and individual flights to uncover performance patterns, delays, cancellations and operational insights.
It is built on three datasets:
	•	airlines.csv - airline codes and names
	•	airports.csv - airport metadata and geolocation
	•	flights_light.csv - flight-level data (times, delays, cancellations, routes)

The goal:
Build a model, clean and analyze the data, and visualize the results in an interactive Tableau dashboard.

⸻

📊 Tableau Dashboard

View the interactive dashboard here:
👉 https://public.tableau.com/app/profile/polina.nechaeva/viz/Airports_Nechaeva/FlightDashboard?publish=yes

Features:
✔ Delay and cancellation analysis
✔ Airline and airport performance comparison
✔ Geo-map of routes
✔ KPI metrics
✔ Filters and drilldowns

⸻

🧩 Dataset Description

Airlines
	•	AIRLINE - airline identifier
	•	IATA_CODE - IATA code

Airports
	•	IATA_CODE - airport identifier
	•	AIRPORT - airport name
	•	CITY, STATE, COUNTRY
	•	LATITUDE, LONGITUDE

Flights

Includes:
	•	Schedule and actual times
	•	Delays (departure, arrival)
	•	Reasons for cancellation
	•	Route information (origin and destination)
	•	Taxi times, air time, elapsed time

Dataset specification is available in the attached project description PDF:
📄 Final Project Tableau_LfS (4).pdf  ￼

⸻

🛠 Technical Steps

1. Data Cleaning
	•	Normalized IATA codes
	•	Checked airport names and removed duplicates
	•	Converted time formats (HHMM to minutes)
	•	Repaired missing values

2. Data Modeling

Relational model using physical joins:
	•	Airlines ↔ Flights via AIRLINE
	•	Airports ↔ Flights via ORIGIN_AIRPORT and DESTINATION_AIRPORT

(According to pages 2-4 of the project requirements PDF)  ￼

3. Analytics
	•	Delay distribution
	•	Cancellation reasons
	•	Airport performance
	•	Airline performance
	•	Route duration and distance

4. Tableau Visualization

Requirements implemented:
	•	KPI metrics
	•	Timeline
	•	Dual-axis charts
	•	Parameter controls
	•	Filter types
	•	Navigation buttons
	•	UX/UI layout using Gestalt principles

⸻

📈 Key Insights
	•	Delays cluster around specific airports
	•	Cancellation behavior varies strongly by airline
	•	Weather-driven patterns visible in several regions
	•	Late aircraft preparation is a recurring delay factor
	•	Certain routes are consistently underperforming

⸻

📁 Repository Structure

Aviation-Analytics-Project/
│
├── datasets/
│   ├── airlines.csv
│   ├── airports.csv
│   └── flights_light.csv
│
├── dashboard/
│   └── Airports_Nechaeva.twbx
│
├── documentation/
│   └── Final Project Tableau_LfS (4).pdf
│
└── README.md


⸻

🧰 Tools & Technologies
	•	Tableau
	•	Python (Pandas)
	•	SQL
	•	Data modeling and joins
	•	Geo-visualization
	•	ETL basics

⸻

👩‍💻 Author

Polina Nechaeva - Data & BI Analyst
📧 panechaeva@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/polina-nechaeva
🐙 GitHub: https://github.com/PolinaLinaNechaeva
