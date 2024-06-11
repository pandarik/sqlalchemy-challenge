# sqlalchemy-challenge
Module 10 Challenge

# Background
Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii. To help with your trip planning, you decide to do a climate analysis about the area. The following sections outline the steps that you need to take to accomplish this task.

## Climate Analysis Instructions
# Part 1: Analyze and Explore the Climate Data
In this section, we will use Python and SQLAlchemy to perform a basic climate analysis and explore the climate database. Follow these steps:

1. Setup Environment:
Ensure you have Jupyter Notebook installed in your Python environment.
Use %matplotlib inline at the beginning of your notebook to display Matplotlib plots inline.
Import necessary libraries: matplotlib, numpy, pandas, datetime, and sqlalchemy.

2. Reflect Tables into SQLAlchemy ORM:
Create an engine to connect to the SQLite database (hawaii.sqlite).
Reflect the existing database into a new model and reflect the tables.
3. Exploratory Precipitation Analysis:
Find the most recent date in the dataset.
Design a query to retrieve the last 12 months of precipitation data and plot the results.
Calculate summary statistics for the precipitation data.
4. Exploratory Station Analysis:
Calculate the total number of stations in the dataset.
Find the most active stations and list them with their observation counts.
Calculate the lowest, highest, and average temperature for the most active station.
Query the last 12 months of temperature observation data for the most active station and plot the results as a histogram.
5. Closing Session:
Close the SQLAlchemy session to clean up resources.


# Running the Jupyter Notebook
1. Open the Notebook:
Upload the Jupyter Notebook to your Jupyter environment.
2. Execute the Cells:
Run each cell in the notebook sequentially to perform the analysis step by step.
2. Review Results:
Check the output of each cell to view the precipitation data, station statistics, and temperature observations.
By following these instructions, you can effectively analyze and explore the climate data using Python libraries and SQL queries.

Here's the Jupyter Notebook link:
https://github.com/pandarik/sqlalchemy-challenge/blob/main/SurfsUp/climate_starter.ipynb




## Part 2: Climate App API with Flask
This repository also contains a Flask-based API for retrieving climate data. The API provides endpoints for precipitation, station information, temperature observations, and temperature statistics.

# Getting Started
1. Installation:
Make sure you have Python and pip installed.
Install the required packages using the following command:
pip install flask flask-restful flasgger

2. Running the API:
Clone this repository to your local machine.
Navigate to the project directory.
Run the Flask app:
Here's the python app.py link:
https://github.com/pandarik/sqlalchemy-challenge/blob/main/SurfsUp/app.py


4. Endpoints:
Precipitation Data:
Endpoint: /api/v1.0/precipitation
Returns a JSON representation of precipitation data for the last year.

Stations:
Endpoint: /api/v1.0/stations
Returns a JSON list of available weather stations.

Temperature Observations:
Endpoint: /api/v1.0/tobs
Returns temperature observations for the most active station in the last year.

Temperature Statistics:
Endpoint: /api/v1.0/<start> (with optional <end> parameter)
Returns minimum, average, and maximum temperatures for a specified date range.

# Command line to add files to the repository
create repo on githib
clone repo - glit cone and key

download files and starter code

Write part 1 and part 2 code , save, test, commit

(base) pandari@Krishnas-MacBook-Pro sqlalchemy-challenge % git add .        
(base) pandari@Krishnas-MacBook-Pro sqlalchemy-challenge % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.md
	new file:   SurfsUp/Resources/hawaii.sqlite
	new file:   SurfsUp/Resources/hawaii_measurements.csv
	new file:   SurfsUp/Resources/hawaii_stations.csv
	new file:   SurfsUp/app.py
	new file:   SurfsUp/climate_starter.ipynb

(base) pandari@Krishnas-MacBook-Pro sqlalchemy-challenge % git add README.md
(base) pandari@Krishnas-MacBook-Pro sqlalchemy-challenge % git commit -m 'readme'
[main a34e79a] readme
 6 files changed, 20287 insertions(+)
 create mode 100644 SurfsUp/Resources/hawaii.sqlite
 create mode 100755 SurfsUp/Resources/hawaii_measurements.csv
 create mode 100755 SurfsUp/Resources/hawaii_stations.csv
 create mode 100644 SurfsUp/app.py
 create mode 100644 SurfsUp/climate_starter.ipynb
(base) pandari@Krishnas-MacBook-Pro sqlalchemy-challenge % git push
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 329.37 KiB | 2.37 MiB/s, done.
Total 10 (delta 0), reused 0 (delta 0)
To https://github.com/pandarik/sqlalchemy-challenge.git
   839b17c..a34e79a  main -> main
(base) pandari@Krishnas-MacBook-Pro sqlalchemy-challenge % 

# Acknowledgments
Leveraged Google, ChatGPT, and Copoilet as/where needed to develop/validate/troubleshoot code/data/functions. The Python and data science community for their invaluable resources.
