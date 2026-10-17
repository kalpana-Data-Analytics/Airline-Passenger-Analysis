✈️ Airline Passenger & Flight Analysis Dashboard

📌 Project Overview

This project focuses on analyzing airline passenger traffic, flight operations, airport activity, and travel patterns using MySQL, Python, Jupyter Notebook, and Microsoft Power BI.
The objective is to transform raw airline data into meaningful insights by performing SQL-based analysis, exploring data using Python, creating visualizations, and developing an interactive Power BI dashboard.
This project demonstrates an end-to-end data analytics workflow, from importing and querying data to visualization and business reporting.


🎯 Project Objectives

Analyze passenger traffic across origin and destination airports.
Understand flight operations and seat availability.
Compare passenger demand across different routes and cities.
Explore flight distance and travel patterns.
Identify trends in airline activity over time.
Create an interactive Power BI dashboard for data exploration and reporting.
Practice both fundamental SQL queries and advanced analytical problem-solving.


📂 Dataset Description

Dataset file: airport_.csv
The dataset contains 7,000 records and 15 columns related to airline routes, passenger traffic, flights, and airports.


🛠️ Tools & Technologies

MySQL: Data querying, validation, aggregation, and analytical problem-solving.
Python: Data analysis and visualization.
Jupyter Notebook: Interactive analysis and documentation.
PyMySQL: Connecting Python to MySQL.
SQLAlchemy: Database connectivity and SQL query integration in Python.
Pandas: Data manipulation and analysis.
Matplotlib / Seaborn: Data visualization, where used in the notebooks.
Microsoft Power BI: Interactive dashboard development and reporting.
GitHub: Project documentation and version-controlled portfolio presentation.


🔄 Project Workflow

1. Dataset Preparation
Reviewed the airline dataset and its columns.
Examined passenger, flight, seat, route, date, and airport information.
Prepared the data for database analysis.
Considered data quality issues, including missing airport coordinates.

2. MySQL Analysis
Imported the dataset into MySQL and created two SQL analysis files.

SQL File 1: Basic and Business Problem Statements
Focused on fundamental analytical questions, including:
What is the total passenger volume?
How many flights are recorded?
Which origin airports have the highest passenger traffic?
Which destination airports receive the most passengers?
Which routes have the highest passenger counts?
How do passenger volumes vary by flight date?
How do routes compare in terms of distance and flight activity?

SQL File 2: Challenging and Advanced Problem Statements
Focused on more advanced analytical questions, including:
How can routes be ranked by passenger traffic?
Which routes have relatively high or low seat utilization?
How does passenger demand vary across origin and destination cities?
Which routes combine high passenger volumes with frequent flights?
How can monthly or yearly passenger trends be compared?
How can window functions and common table expressions be used to rank and compare routes?
How can analytical metrics help identify routes that may need further operational investigation?


3. Python Analysis Using Jupyter Notebook:

 Notebook(Database connect, Database Insert): Data Exploration and Basic Analysis
Connected to the MySQL database.
Retrieved data using SQL queries.
Explored passenger and flight information.
Examined routes, airports, dates, and distances.
Created visualizations to understand the dataset.

Notebook 2(Airline project): Advanced Analysis and Visualization
Performed deeper analysis of passenger and route patterns.
Compared flight and passenger metrics.
Explored trends and relationships within the data.
Created additional visualizations to support interpretation.


4. Power BI Dashboard

Developed an interactive dashboard in Microsoft Power BI to present key metrics and explore airline activity.

The report includes:
KPI cards: Summary metrics for passengers, flights, and airport or route activity.
Airport maps: Geographic exploration of origin and destination airports.
Airport comparisons: Column charts comparing origin and destination airport activity.
Time-series analysis: Charts for examining trends over flight dates.
Passenger and flight analysis: Visual comparisons of important airline metrics.
Interactive slicers: Filters for flight date, origin city, and destination city.


📊 Key Business Questions

This project explores questions such as:

Which origin and destination airports handle the greatest passenger volumes?
Which routes have the highest passenger demand?
How do passenger numbers compare with available seats?
How does flight activity vary across different routes?
What patterns can be observed in passenger traffic over time?
How do route distance and flight frequency relate to passenger volumes?
Which airports and routes deserve further investigation based on their traffic patterns?


💡 Business Value

The analysis can support exploratory decision-making in areas such as:
Route planning: Identifying routes with relatively high passenger demand.
Capacity planning: Comparing passenger numbers with available seats.
Operational analysis: Examining flight frequency and route activity.
Airport performance monitoring: Comparing traffic across airports and cities.
Trend monitoring: Investigating changes in passenger traffic over time.


📁 Project Structure

Airline-Passenger-Flight-Analysis/
│
├── README.md
│
├── DATA/
│   └── airport_.csv
│
├── SQL/
│   ├── 01_sql_analysis1.sql
│   └── 02_sql_analysis2.sql
│
├── python/
│   ├── 01_Database connect.IPYB
│   └── 02_Database insert.IPYB
│
└── POWER BI/
    └── AIRPOR .PROJECT .PBIX


🚀 How to Explore This Project
Dataset: Review the CSV file and understand the available columns.
MySQL: Open the SQL scripts in MySQL Workbench and review or execute the queries against the imported dataset.
Jupyter Notebook: Open the notebooks in Jupyter and configure the MySQL connection credentials locally.
Python analysis: Run the notebooks to examine the queries, analysis, and visualizations.
Power BI: Open the .pbix report in Power BI Desktop to explore the dashboard.

📚 Skills Demonstrated
SQL querying and data aggregation
Business problem-solving
Basic and advanced analytical queries
MySQL database connectivity
Python data analysis
Pandas data manipulation
Data visualization
Dashboard development
KPI reporting
Interactive data exploration
Data storytelling
Project documentation using GitHub.


👩‍💻 About This Project

This is my second data analytics portfolio project, created to strengthen my practical skills in SQL, Python, data visualization, and Power BI.
It demonstrates my approach to solving analytical problems by combining database querying, exploratory analysis, visualization, and interactive business reporting.

Tools used: MySQL | Python | Jupyter Notebook | PyMySQL | SQLAlchemy | Power BI | GitHub









