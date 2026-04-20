🏏 Cricket Champions Trophy Data Analytics Dashboard
📌 Project Overview

This project presents an interactive Cricket Champions Trophy Data Analytics Dashboard built using Power BI. It analyzes historical match and player data to generate insights on team performance, player achievements, match outcomes, and venue trends.

The project workflow includes:

Data collection from datasets
Data cleaning and preprocessing using Python (Pandas)
Building an interactive dashboard in Power BI
⚙️ Tech Stack
Python (Pandas) → Data cleaning & preprocessing
Power BI → Visualization & dashboard
CSV Files → Data source
Jupyter Notebook → Data processing
📂 Dataset Information

Two datasets were used in this project:

🧑‍💻 Player Dataset

📄 all_champions_trophy_players_list.csv

Columns:

Team – Team name
Year – Tournament year
Player Name – Name of the player
🏏 Match Dataset

📄 all_champions_trophy_matches_results-updated.csv

Columns:

Team1 – First team
Team2 – Second team
Toss – Toss result (team and decision)
Match days – Match type (day/daynight)
Winner – Match winner
Player of the Match – POM winner
Margin – Winning margin
Ground – Venue name
Match Date – Date of match
ODI Int Match – Match number
Team1 Avg Batting Ranking – Avg batting ranking of Team1
Team2 Avg Batting Ranking – Avg batting ranking of Team2
Team1 Avg Bowling Ranking – Avg bowling ranking of Team1
Team2 Avg Bowling Ranking – Avg bowling ranking of Team2
Team1 Total CTs participated – Total CT participation (Team1)
Team1 Total CTs won – Total CT wins (Team1)
Team2 Total CTs participated – Total CT participation (Team2)
Team2 Total CTs won – Total CT wins (Team2)
Team1 W/L ratio over Team2 – Win/Loss ratio comparison
🧹 Data Cleaning & Preprocessing

Performed using Pandas:

Removed missing and duplicate values
Standardized team and match formats
Converted date formats
Extracted insights for dashboard metrics
📊 Dashboard Features
🔹 Key Metrics
Total Matches: 113
Total Players: 119
Total Teams: 8
Total Wins: 89
Total POM Awards: 15
First POM Winner: Abdul Razzaq
🔹 Visualizations
📊 Teams Total Wins (Bar Chart)
🥧 Total Wins by Ground (Pie Chart)
🍩 Match Result by Toss Decision (Donut Chart)
📊 Most Player of Match Awards (Bar Chart)
📊 Batting Ranking by Match Type
🥧 Winning Margin Distribution
🔹 Filters (Slicers)
Year
Team
Match Format (Day / Day-Night)
📈 Key Insights
India has the highest number of wins
Day-Night matches show better batting performance
Venues like The Oval and Birmingham host more matches
Toss decisions impact match outcomes
