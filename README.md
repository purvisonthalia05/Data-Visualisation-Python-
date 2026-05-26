# Data-Visualisation-Python-

1. Car & Cereal Dataset Analysis

A Python data analysis project exploring two real-world datasets — the mtcars automobile dataset and a cereal nutrition dataset — using Pandas, Matplotlib, and Seaborn.
Objective

Perform statistical analysis on car performance metrics (MPG, horsepower, weight, cylinders)
Analyze cereal nutrition data (calories, sugar, fiber, rating)
Visualize relationships between variables using scatter plots, box plots, and bar charts
Draw data-driven conclusions about fuel efficiency and healthy cereal choices

Datasets Used

DatasetDescriptionmtcars.csv32 car models with attributes like MPG, horsepower, weight, cylinders, and transmission typecereal.csv77 breakfast cereals with nutritional values including calories, sugar, fiber, fat, and ratings

Tech Stack
Python 3 — Pandas, NumPy, Matplotlib, Seaborn

Analysis Performed

Descriptive statistics for MPG, horsepower, and weight
Line plot: Cylinders vs Fuel Efficiency | Scatter plot: Horsepower vs MPG
Box plot: MPG by transmission type (Automatic vs Manual)
Seaborn scatter with model-wise hue to identify high-efficiency, high-HP cars
Bar plot: Sugar content per cereal | Scatter: Calories vs Fat with brand hue

Key Findings

As horsepower increases, MPG decreases — Ferrari Dino stands out as the highest efficiency, high-HP car
Manual transmission cars generally achieve better MPG than automatic
All-Bran with Extra Fiber is the healthiest cereal based on lowest calorie and fat content
Lower-calorie cereals tend to receive higher consumer ratings

2. IPL Match Analysis
   
A Python data analysis project exploring Indian Premier League match data to uncover performance trends, team dominance, player achievements, and venue statistics.

Objective

Analyze IPL match records across multiple seasons
Identify top-performing teams, players, and venues
Visualize match trends, win patterns, and home vs away performance
Track season-by-season performance for the most successful team

Dataset Used

ipl_full_matches.csv — Complete IPL match records including teams, venues, winners, player of the match, and season data

Tech Stack

Python 3 — Pandas, Matplotlib, Seaborn

Analysis Performed

Total matches, teams, and seasons summary
Matches per season — bar chart
Top 5 teams with most wins — annotated horizontal bar chart
Top 10 players by Player of the Match awards
Top 10 venues by match count — pie chart
Home vs Away wins comparison
Season-wise wins trend for the most successful team — line chart

Key Findings

A clear dominant team emerges across IPL seasons based on total win count
Home advantage shows a measurable difference in win rates
A small group of players repeatedly win Player of the Match awards
Certain venues consistently host more matches
