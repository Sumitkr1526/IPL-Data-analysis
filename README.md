# IPL Data Analysis Dashboard
📌 Project Overview

This project provides a comprehensive analysis of the Indian Premier League (IPL) using Python and Power BI. The dashboard leverages match-level and ball-by-ball datasets to uncover insights into team performance, player statistics, batting and bowling trends, venue impact, toss decisions, and season-wise comparisons.

The goal is to transform raw IPL data into meaningful visualizations and actionable insights through data analysis and business intelligence techniques.

## Dataset

The project uses two datasets:

1. Matches Dataset (matches.csv)

Contains match-level information:

Match ID
Season
Teams
Venue
Toss Winner
Match Winner
Player of the Match
Win Margin

2. Deliveries Dataset (deliveries.csv)

Contains ball-by-ball information:

Match ID
Batting Team
Bowling Team
Batsman
Bowler
Runs Scored
Extras
Wickets

## Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Power BI
DAX (Data Analysis Expressions)

## Dashboard Features
### Executive Overview
Total Matches
Total Seasons
Total Runs
Total Wickets
Total Fours
Total Sixes

### Team Analysis
Team-wise Wins
Toss Impact Analysis
Team Run Comparison
Team Wicket Comparison

### Player Analysis
Top Run Scorers
Top Wicket Takers
Strike Rate Analysis
Player of the Match Awards

### Batting Insights
Boundary Analysis
Powerplay Performance
Death Overs Analysis
Run Rate Trends

### Venue Analysis
Matches by Venue
Average Venue Scores
Winning Trends Across Venues

## Key Insights
Identified the most successful IPL franchises across seasons.
Analyzed the impact of toss decisions on match outcomes.
Compared batting and bowling performances of top players.
Evaluated scoring patterns during powerplay and death overs.
Examined venue-specific trends and average scoring behavior.

## Data Model
matches[id]
        |
        |
        |
deliveries[match_id] (*)

Relationship Type:
One-to-Many
Cross Filter Direction: Single

## How to Run
Python Analysis
pip install pandas numpy matplotlib seaborn

Run the Jupyter Notebook:
jupyter notebook

## Power BI Dashboard
1. Open Power BI Desktop
2. Import matches.csv and deliveries.csv
3. Create relationship:
matches[id]
deliveries[match_id]
4. Add DAX measures
5. Build dashboard visuals
6. Publish to Power BI Service

##  Dashboard Preview
<img width="1137" height="652" alt="image" src="https://github.com/user-attachments/assets/fbcfe5a6-731b-418d-bd7b-bb9700a49675" />


/dashboard-images
    overview.png
    team-analysis.png
    player-analysis.png

    
## Project Structure
IPL-Data-Analysis/
│
├── data/
│   ├── matches.csv
│   └── deliveries.csv
│
├── notebooks/
│   └── IPL_Data_Analysis.ipynb
│
├── powerbi/
│   └── IPL_Dashboard.pbix
│
├── dashboard-images/
│   └── screenshots
│
├── README.md
│
└── requirements.txt

## Future Enhancements
Win Probability Analysis
Predictive Match Outcome Modeling
Player Performance Forecasting
Interactive Web Dashboard using Streamlit
Advanced Cricket Analytics Metrics

## Author

Sumit Kumar

Data Analytics | Python | SQL | Power BI 

⭐ If you found this project useful, consider giving it a star!
