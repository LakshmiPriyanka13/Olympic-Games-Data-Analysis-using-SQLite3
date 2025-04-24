# Olympic-Games-Data-Analysis-using-SQLite3
This repository contains a comprehensive analysis of Olympic Games data, exploring athlete demographics, medal distributions, and nation-level performance through SQL and Python

## Contents
<a href="https://github.com/LakshmiPriyanka13/Olympic-Games-Data-Analysis-using-SQLite3/blob/main/athlete_events.csv">athlete_events.csv</a>: Contains detailed records of athletes who have participated in the Olympics, including information like age, height, weight, team, event, and medals won          
<a href="https://github.com/LakshmiPriyanka13/Olympic-Games-Data-Analysis-using-SQLite3/blob/main/noc_regions.csv">noc_regions.csv</a>: Maps National Olympic Committee (NOC) codes to their respective regions and notes            
<a href="https://github.com/LakshmiPriyanka13/Olympic-Games-Data-Analysis-using-SQLite3/blob/main/data%20analysis.db">data analysis.db</a>: SQLite database file that stores structured data in two main tables:        
OLYMPICS_HISTORY: Loaded from athlete_events.csv               
OLYMPICS_HISTORY_NOC_REGIONS: Loaded from noc_regions.csv                      
SQL for data analysis.ipynb: Jupyter notebook showcasing how the raw data is loaded into SQL, along with various analytical queries to uncover insights

## Objectives
- Perform data cleaning and transformation
- Store Olympic data efficiently using SQL
- Run SQL queries to:
    Analyze medal trends over time
    Compare performance across countries and genders
    Understand athlete characteristics like age, height, and weight

## Tools & Technologies
- Python (pandas, sqlite3): For data handling and transformation.
- Jupyter Notebook: Interactive environment for exploration and analysis.
- SQLite: Lightweight database engine for structured storage and querying.

## Sample Analyses
Some of the insights explored in the notebook:
- Medal tally by countries over the years.
- Gender distribution in various sports.
- Age and physical metrics of medal-winning athletes.


