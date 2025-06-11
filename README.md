
# 🏏 Cricket Dream Team Selector – T20 World Cup 2022-23 
(https://project.novypro.com/eU32JC)

## 📌 Problem Statement
This project focuses on building a data-driven Dream Team of 12 players from all participating nations in the ICC Men’s T20 World Cup 2022-23. Using real-time match data, the goal is to identify top-performing players across batting, bowling, and all-rounder roles based on statistical metrics, without any personal bias.

The project integrates web scraping, data cleaning, statistical modeling, and interactive visualizations in Power BI to arrive at a well-balanced, high-impact cricket squad.

## 🔄 Steps Followed
### 1. Data Collection
Extracted match data from the official ESPN Cricinfo T20 World Cup 2022-23 page.

Used two scraping tools:

Bright Data – used JavaScript code and proxies for dynamic scraping.

ParseHub – enabled quick, no-code scraping for tabular data.

Downloaded and processed four key datasets in JSON format:

Match Summary

Player Info

Batting Summary

Bowling Summary

### 2. Data Preprocessing (Python – Jupyter Notebook)
Created a match ID dictionary to map teams with their unique matches.

Cleaned data by:

Removing inconsistent symbols, nulls, and special characters.

Normalizing player names and converting JSONs to CSVs.

Used Python libraries like pandas, json, and re for transformation.

### 3. Data Modeling & Transformation (Power BI – Power Query)
Imported cleaned CSVs into Power BI and performed:

Data profiling (column quality, distribution, and profiling).

Null/duplicate removal and schema alignment.

Table relationships using player names and match IDs.

### 4. Feature Engineering (DAX & Power BI Modeling)
Created custom DAX measures for:

Batting: Runs, Strike Rate, 30+ scores, Boundary %, Dot %, Dismissals.

Bowling: Wickets, Economy Rate, Dot %, Avg Runs per Wicket.

All-Rounders: Combined impact score.

Calculated columns to categorize player roles (Opener, Top Order, Middle Order, etc.).

### 5. Dashboard Creation & Interactivity
Developed individual dashboards for:

Openers, Top Order, Middle Order, All-Rounders, Bowlers

Used advanced visualizations:

Matrix, Card, and Table visuals for player rankings.

Slicers for team, role, and performance thresholds.

Tooltip pages with hover-based player detail cards.

Drill-through actions to deep dive into individual stats.

Conditional formatting to highlight top performers.

### 6. Final Team Formation
Applied performance filters and ranking logic to select the top players in each role.

Built the final Best XII Squad View based on:

Balanced player distribution

Role coverage

Impact and consistency across matches

## 📊 Tools & Technologies Used
Data Collection: Bright Data, ParseHub

Preprocessing: Python, Jupyter Notebook

Visualization: Power BI Desktop

Languages: Python, DAX, Power Query (M)

## 🌟 Outcome
Identified the top 12 players of the tournament based on performance analytics.

Delivered a dynamic and fully interactive Power BI dashboard.

Enabled data-driven team selection based on objective KPIs like strike rate, wickets, economy, and batting average.

## 🧠 Key Learnings
End-to-end workflow from web scraping to dashboard publishing

Advanced DAX usage and Power Query transformations

Importance of interactivity, storytelling, and UI design in dashboards
