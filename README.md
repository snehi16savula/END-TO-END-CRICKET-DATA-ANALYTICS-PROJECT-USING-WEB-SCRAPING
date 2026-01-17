This project demonstrates a full data analytics lifecycle applied to cricket match data, starting from web scraping raw data to building insightful dashboards for analysis and decision-making.

The goal is to collect real-world cricket data, clean and transform it, store it efficiently, and perform exploratory and performance analysis using modern analytics tools.

 Objectives

Scrape live or historical cricket data from the web

Clean and preprocess raw, unstructured data

Perform exploratory data analysis (EDA)

Generate meaningful cricket insights

Visualize player and team performance

 Architecture
Web Source
   ↓
Web Scraping 
   ↓
Raw Data 
   ↓
Data Cleaning & Transformation
   ↓
Analytics Dataset
   ↓
Visualization & Insights

Data Source

Match, player, and scorecard data scraped from public cricket websites such as ESPN Cricinfo

Data includes:

Match details

Batting statistics

Bowling statistics

Team performance

This project is for educational purposes only and respects website scraping policies.

 Tech Stack

Python – Core programming language

BeautifulSoup – Web scraping

Pandas & NumPy – Data cleaning and analysis

SQL – Data storage and querying

Matplotlib – Data visualization

Power BI  – Interactive dashboards

Jupyter Notebook – Analysis workflow

Project Structure
cricket-data-analytics
│
├── scraping
│   ├── scrape_matches.py
│   ├── scrape_scorecards.py
│
├── data
│   ├── raw
│   ├── processed
│
├── notebooks
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│
├── dashboards
│   ├── cricket_dashboard.pbix
│
├── sql
│   ├── table_schema.sql
│


 Key Insights Generated

Best-performing batsmen and bowlers

Team win percentages

Impact of toss on match results

Player consistency across formats

Performance trends over time
