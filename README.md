Cricket Champions Trophy Data Analytics Dashboard
Overview

This project presents a data analytics dashboard for the ICC Champions Trophy using Power BI. It focuses on analyzing match results, player participation, and team performance to generate meaningful insights.

The workflow includes data collection, preprocessing using Python (Pandas), and dashboard development in Power BI.

Tech Stack
Python (Pandas) – Data cleaning and preprocessing
Power BI – Data visualization
CSV – Data source
Jupyter Notebook – Data processing
Datasets
1. Player Dataset

File: all_champions_trophy_players_list.csv

Columns:

Team
Year
Player Name
2. Match Dataset

File: all_champions_trophy_matches_results-updated.csv

Columns:

Team1
Team2
Toss
Match days
Winner
Player of the Match
Margin
Ground
Match Date
ODI Int Match
Team1 Avg Batting Ranking
Team2 Avg Batting Ranking
Team1 Avg Bowling Ranking
Team2 Avg Bowling Ranking
Team1 Total CTs participated
Team1 Total CTs won
Team2 Total CTs participated
Team2 Total CTs won
Team1 W/L ratio over Team2
Data Processing
Removed missing and duplicate values
Standardized data formats
Converted date fields
Prepared data for visualization
Dashboard Features
Team-wise total wins
Match results based on toss decisions
Player of the Match analysis
Venue-based performance
Match type comparison (Day vs Day-Night)
Winning margin distribution
Key Insights
Certain teams dominate overall wins
Toss decisions influence match outcomes
Specific venues host more matches
Day-Night matches show different performance trends
How to Use
Clone the repository
Open the .pbix file in Power BI
Use filters to explore the dashboard
Project Structure
data/
  all_champions_trophy_players_list.csv
  all_champions_trophy_matches_results-updated.csv
notebooks/
  data_cleaning.ipynb
dashboard/
  cricket_dashboard.pbix
README.md
