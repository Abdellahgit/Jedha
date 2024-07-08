# Jedha-Project
What's the Best Place to Be a Data Analyst in the US
Overview
This project aims to determine the best place to be a Data Analyst in the United States by analyzing various datasets. The analysis considers multiple factors such as salaries, job offers, cost of living, and weather conditions.

Datasets
We utilized the following datasets in this project:

Salaries Data - Sourced from Kaggle
Job Offers Data - Sourced from Kaggle
Cost of Living Data - Sourced from Kaggle
Weather Data - Created using the OpenWeather API

Project Workflow

1. Data Exploration and Cleaning
Tools Used: Python, Power BI
Tasks:
Exploring and cleaning the data
Removing unnecessary columns
Trimming and changing data types
Creating links between datasets by generating a primary key column that served as a foreign key in other datasets

2. Weather Data Extraction and Transformation
API Used: OpenWeather API
Tasks:
Extracting weather data
Transforming the data from daily format to monthly and yearly aggregates

3. Data Integration
Tools Used: Power BI
Tasks:
Uploading all datasets into a single Power BI file
Creating relationships between the different tables

4. Scoring System
Tasks:
Developing a scoring system based on key variables
Creating a total score to rank the states
Conclusion
By integrating multiple datasets and analyzing key variables, this project aims to provide insights into the best places in the US for Data Analysts based on salaries, job opportunities, cost of living, and weather conditions.

Tools and Technologies
Python
Power BI
OpenWeather API
Kaggle Datasets



The "posting.csv" file has been pre-modified because of it's weight (over 500Mo) and couldn't be uploaded easily
The change resolve simply around deleting a column called "Description" which was the details of each job offer, but weighted about 450Mo 
The Git submit limit by defaults are 100Mo files so I prefered to do a manual tweak here 

The original file (and full folder) can be found there : https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data

