Cleaned Urban Noise Data

Overview

This dataset contains cleaned and preprocessed urban noise measurements collected from various sensors in the city. The data has been prepared for further analysis or integration into databases and machine learning workflows.

All transformations including missing value handling, duplicate removal, and ID reordering were performed using PySpark.


Dataset Columns
	•	id: Unique record identifier (int)

	•	latitude: Latitude of the measurement location (double)

	•	longitude: Longitude of the measurement location (double)

	•	datetime: Date and time of measurement (timestamp)

	•	decibel_level: Noise level in decibels (double)

	•	hour: Hour of the day (0–23) (int)

	•	day_of_week: Day of the week (1 = Monday, 7 = Sunday) (int)

	•	is_weekend: 1 if weekend, 0 if weekday (int)

	•	temperature_c: Temperature in Celsius (double)

	•	humidity_%: Relative humidity (%) (double)

	•	wind_speed_kmh: Wind speed in km/h (double)

	•	precipitation_mm: Precipitation in mm (double)

	•	traffic_density: Traffic density measurement (int)

	•	near_airport: 1 if near an airport, 0 otherwise (int)

	•	near_highway: 1 if near a highway, 0 otherwise (int)

	•	near_construction: 1 if near construction sites, 0 otherwise (int)

	•	population_density: Local population density (int)

	•	park_proximity: 1 if near a park, 0 otherwise (int)

	•	industrial_zone: 1 if near industrial area, 0 otherwise (int)

	•	vehicle_count: Number of vehicles recorded (int)

	•	honking_events: Number of honking events detected (int)

	•	public_event: 1 if a public event occurred, 0 otherwise (int)

	•	holiday: 1 if a public holiday, 0 otherwise (int)

	•	school_zone: 1 if near a school, 0 otherwise (int)

	•	noise_complaints: Number of noise complaints reported (int)

	•	sensor_id: ID of the sensor capturing data (int)



Data Cleaning & Transformation
	1.	Verified no missing values.
	2.	Removed duplicate records.
	3.	Reordered IDs sequentially after cleaning.
	4.	Checked data types for correctness.
	5.	Dataset is structured for loading into SQL or other storage systems.



Files Included
	•	urban_noise_levels.csv – Cleaned CSV dataset.
	•	README.md – This documentation.



Usage Notes
	•	Use for data analysis, visualization, or machine learning.
	•	Processing done using PySpark in Google Colab.
	•	Dataset contains no personal or sensitive information.

