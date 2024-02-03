# Project Name
sqlalchemy_challenge
## Overview
Use Python and SQLAlchemy to do a basic climate analysis and data exploration of a climate database. Specifically, use SQLAlchemy ORM queries, Pandas, and Matplotlib.
## Brief description of the project.
Use provided dataset to do climate analysis and data exploration. Project includes using SQLAlchemy function to connect to SQLite database.
Use SQLAlchemy function to connect to SQLite database. This project links python to the database by creating a SQLAlchemy session and performs percipitation analysis using previous 12 months of data.

## Table of Contents

## Required Libraries
- The project requires the following Python libraries:
- pandas
- sqlalchemy
- PostgreSQL
- Json
- Matplotlib
## Installation
-Installing PostgreSQL:
   1. Download the PostgreSQL installer for your operating system from the official website.
   2. Run the installer and follow the instructions to set up the password, port number, and data directory.
   3. Ensure that you add PostgreSQL to your PATH when presented with the option.
-Installing pgAdmin:
   1. Download the pgAdmin installer for your operating system from the official website.
   2. Run the installer and follow the instructions to complete the installation.
- Installing Python:
  1. Download the latest version of Python from the official website.
  2. Run the installer and follow the instructions to complete the installation.
  3. Ensure that you add Python to your PATH when presented with the option.
- Installing Dependencies:
  1.Open the command prompt or terminal.
  2.Navigate to the project directory.
  3.Run the following command to install the dependencies: pip install -r requirements.txt
## Usage
To run scripts in python, we will use libraries above to analyze data using python. Scripts are run in Anaconda prompt by opening the terminal and navigating to the directory where the script is located.
Python scripts can be ran using the command python script_name.py
## Data
Two datasets used in this project included Precipitation data and station data in the islands of Hawaii. 
## Analysis
Two analysis were performed on this project. 
  1. Preciptation Analysis
       - Most recent date was used in a 12 month dataset to precipitation information.
       - Pandas was used to print the summary statistics for the precipitation data.
  2. Station Analysis
       - Query was designed to calculate the total number of stations in the dataset.
       - Most active stations were queried
       - Query designed was then used to calculate the lowest, highest and average temperatures that filtered the most active station id.
       - 12 months of temperature observation data was used for station analysis.
  3. Climate App Design
      -  Design a Flask API based on queries developed from above
  
## Results
See attached Jupyter Notebook for Climate and Data Analysis and Flask API 
## License
Menne, M.J., I. Durre, R.S. Vose, B.E. Gleason, and T.G. Houston, 2012: An overview of the Global Historical Climatology Network-Daily Database. Journal of Atmospheric and Oceanic Technology, 29, 897-910, https://journals.ametsoc.org/view/journals/atot/29/7/jtech-d-11-00103_1.xmlLinks to an external site..


