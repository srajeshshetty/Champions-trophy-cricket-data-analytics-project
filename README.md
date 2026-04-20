Cricket Champions Trophy Data Analytics Dashboard
Overview

This project presents a Power BI dashboard built on ICC Champions Trophy data.
It involves data preprocessing using Python (Pandas) and visualizing match outcomes, player performance, and team statistics.

Tech Stack
Python (Pandas)
Power BI
CSV Files
Datasets
Player Dataset

all_champions_trophy_players_list.csv

Columns:

Team
Year
Player Name
Match Dataset

all_champions_trophy_matches_results-updated.csv

Columns:

Team1, Team2, Toss, Match days, Winner
Player of the Match, Margin, Ground, Match Date
ODI Int Match
Team1 Avg Batting Ranking, Team2 Avg Batting Ranking
Team1 Avg Bowling Ranking, Team2 Avg Bowling Ranking
Team1 Total CTs participated, Team1 Total CTs won
Team2 Total CTs participated, Team2 Total CTs won
Team1 W/L ratio over Team2


Data Processing
Removed missing and duplicate values
Standardized formats
Prepared datasets for visualization

Dashboard Features

Team performance analysis
Toss vs match result
Player of the Match insights
Venue-based trends
Match type comparison

Key Insights
Toss outcome influences match results
Certain players frequently win Player of the Match
Match results vary across different Ground
Rankings (batting and bowling) impact team performance
Historical stats and W/L ratio affect outcomes

Usage
Clone the repository
Open the .pbix file in Power BI
Explore the dashboard using filters
Project Structure
data/
dashboard/
notebooks/
README.md
