# IPL Data Analytics & Business Intelligence Project

## Overview

This project performs an end-to-end analysis of Indian Premier League (IPL) historical data using Python.

The goal is to transform raw match-level and ball-by-ball datasets into meaningful business insights through data cleaning, exploratory data analysis (EDA), and interactive visualizations.

The analysis focuses on identifying performance trends, winning strategies, team consistency, scoring patterns, toss impact, venue advantages, and historical team comparisons.

## Project Visualizations

### Number of Matches Played

![Matches Played](No%20of%20matches%20played.png)

### Teams with Most Matches Played

![Teams Played](teams%20with%20most%20matches%20played.png)

### Teams with Highest Win Percentage

![Win Percentage](teams%20with%20highest%20win%20percentage.png)

### Toss Decision Trend

![Toss Trend](toss%20decision%20trend.png)

### IPL Winners Over the Years

![IPL Winners](ipl%20winners%20over%20the%20years.png)

---

## Business Problem

Sports organizations, broadcasters, analysts, and franchise owners require data-driven insights to understand team performance and optimize decision-making.

Raw IPL datasets contain thousands of records, making it difficult to extract actionable information directly.

This project answers key questions such as:

* Which teams have been the most successful historically?
* Does winning the toss increase the probability of winning the match?
* How have scoring patterns evolved over the seasons?
* Which venues provide advantages to specific teams?
* Which teams are the most consistent performers?
* What are the biggest winning margins in IPL history?

---

## Dataset

The project uses two IPL datasets:

### Matches Dataset

Contains:

* Match ID
* Season
* Teams
* Venue
* Toss winner
* Toss decision
* Match winner
* Player of the Match
* Winning margins

### Deliveries Dataset

Contains:

* Ball-by-ball information
* Runs scored
* Innings details
* Batting team
* Bowling team
* Extras

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

Imported IPL Matches and Deliveries datasets.

### 2. Data Cleaning

* Removed unnecessary columns
* Handled missing values
* Validated dataset quality
* Optimized datasets for analysis

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

#### Season Analysis

* Number of matches per season
* Scoring trends across seasons

#### Toss Analysis

* Toss decision trends
* Toss impact on match outcomes

#### Team Performance

* Teams with most matches played
* Teams with highest wins
* Win percentage analysis

#### Championship Analysis

* IPL winners by season
* Franchise success comparison

#### Consistency Analysis

* Most consistent team
* Least consistent team

#### Venue Analysis

* Team-wise lucky venues
* Venue impact on winning probability

#### Match Insights

* Largest victory margins
* Head-to-head team comparison

#### Scoring Analysis

* Total runs across seasons
* Runs scored per match
* Batting first vs batting second comparison

---

## Key Insights

### Toss Impact

Winning the toss provides a noticeable advantage, but does not guarantee match victory.

### Scoring Trends

Average runs per match have increased over the years, indicating a more aggressive batting approach.

### Team Success

Mumbai Indians and Chennai Super Kings emerged as the most successful franchises historically.

### Venue Advantage

Certain teams show significantly stronger performance at specific venues.

### Consistency

Some franchises maintain performance levels across seasons, while others show high variability.

---

## Business Value

The insights generated from this analysis can help:

* Team management evaluate performance trends
* Coaches identify strategic advantages
* Broadcasters create data-driven storytelling
* Sponsors understand team popularity and success
* Analysts make evidence-based predictions

---

## Future Enhancements

* Interactive Power BI Dashboard
* Predictive Match Outcome Model
* Player Performance Analytics
* Real-Time IPL Data Integration
* Machine Learning-based Win Prediction

---

## Author

Vidhit Bokadey

Business Intelligence Developer | Data Analyst | Power BI Developer

Specializing in Data Analytics, Dashboarding, SQL, Python, and Business Intelligence.
