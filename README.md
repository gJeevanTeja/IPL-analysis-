📌 Project Overview
This project analyzes a comprehensive dataset of IPL matches spanning from the inaugural 2008 season to 2017. The goal was to uncover the "hidden patterns" behind winning streaks, the significance of the toss, and identifying the most impactful players across a decade of cricket.

📊 The Dataset
The analysis is based on a dataset of 636 matches, featuring columns such as:

Match Context: Season, City, Date, and Venue.

Team Dynamics: Team 1, Team 2, Toss Winner, and Toss Decision.

Outcomes: Winner, Result Type (Normal/DL), and Win Margin (Runs/Wickets).

Individual Brilliance: Player of the Match and Umpire details.

🛠️ Data Pipeline
1. Data Cleaning (Python & Pandas)
Handling City Mismatches: Fixed missing city values (e.g., identifying venues like Dubai/Sharjah).

Standardization: Unified team names that changed over time (e.g., Rising Pune Supergiant vs Supergiants).

Data Type Correction: Converted date strings into datetime objects for chronological trend analysis.

2. Exploratory Data Analysis (SQL & Pandas)
I performed deep-dive queries to answer:

Toss Strategy: Does "Fielding First" actually lead to more wins?

Venue Dominance: Which stadiums are "high-scoring" versus "bowler-friendly"?

Performance Trends: Which team has the highest win percentage across all 10 seasons?

3. Visualization (Power BI)
I built an interactive dashboard to visualize:

The Winning Factor: A breakdown of matches won by runs vs. wickets.

Player of the Match Leaderboard: Highlighting top-tier performers like Chris Gayle and Yusuf Pathan.

Seasonal Growth: The number of matches and total runs scored per year.

📈 Key Insights from the Data
1) Identified the no of the wins in each season
2) 98% matches shows the normal result
3) 57% teams choose the fielding
4) In the venues i have identified highest used stadium is chinnaswammy 
