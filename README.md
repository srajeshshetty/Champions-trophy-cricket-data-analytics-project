Cricket Champions Trophy Data Analytics Dashboard
Overview

This project is a Power BI dashboard analyzing ICC Champions Trophy data.
It uses Python (Pandas) for data cleaning and focuses on match results, player impact, and team performance.

Tech Stack
Python (Pandas)
Power BI
CSV
Datasets

Player Dataset (all_champions_trophy_players_list.csv)

Team
Year
Player Name

Match Dataset (all_champions_trophy_matches_results-updated.csv)

Team1, Team2, Toss, Match days, Winner
Player of the Match, Margin, Ground, Match Date
ODI Int Match
Team1 Avg Batting Ranking, Team2 Avg Batting Ranking
Team1 Avg Bowling Ranking, Team2 Avg Bowling Ranking
Team1 Total CTs participated, Team1 Total CTs won
Team2 Total CTs participated, Team2 Total CTs won
Team1 W/L ratio over Team2
Processing
Cleaned missing and duplicate data
Standardized formats
Prepared data for dashboard
Features
Team wins analysis
Toss vs match result
Player of the Match analysis
Venue-based insights
Match type comparison
Insights
Winner is often influenced by Toss outcome
Repeated names in Player of the Match show key performers
Ground impacts match results and frequency
Match days affects match patterns
Better batting and bowling rankings improve win chances
Historical stats and W/L ratio influence outcomes
Usage
Clone the repository
Open .pbix in Power BI
Explore using filters
Structure
data/
dashboard/
notebooks/
README.md
