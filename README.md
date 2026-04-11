🎬 Pixar Studios Analytics Dashboard (Power BI)
📌 Project Overview

This project presents a comprehensive Power BI dashboard analyzing Pixar movies across financial performance, audience reception, and critical success.

The dashboard combines multiple datasets to provide a 360° view of Pixar’s filmography, enabling users to explore trends, profitability, audience ratings, and contributor impact.

🎯 Objectives
Analyze overall performance of Pixar films
Track box office trends over time
Compare budget vs worldwide revenue
Understand audience ratings and sentiment
Explore genre distribution and content strategy
Identify contributions of directors, writers, and creators
📂 Data Source

The dataset for this project was sourced from Kaggle.

Datasets Used:
Pixar Films – Film details (title, release date, ratings)
Box Office – Budget and worldwide revenue
Academy Awards – Awards and recognition
Genre – Film categories
Pixar People – Contributors (Director, Writer, etc.)
Public Response – IMDb, Rotten Tomatoes, CinemaScore
🔧 Data Preparation (Power Query)

Key transformations performed:

Promoted headers and corrected data types
Renamed columns for consistency
Handled missing values:
Budget → Filled using external verified sources
CinemaScore → Mode imputation (most frequent value)
Standardized ratings (G, PG categories)
🧩 Data Modeling
Star Schema Design
Fact Table: Pixar Films
Dimension Tables:
Box Office, Academy Awards, Genre, People, Public Response
Relationships:
One-to-Many relationships using film column
Optimized for performance and scalability
📊 Dashboard Features
🔹 KPI Cards
Total Films
Total Budget
Total Box Office Revenue
Awards Won
Avg IMDb Rating
Avg Rotten Tomatoes Score
📈 Visualizations
Line Chart → Box Office Trend by Year
Clustered Bar Chart → Budget vs Revenue
Donut Chart → Genre Distribution
Bar Chart → Awards by Film
Column Chart → Movie Ratings (G vs PG)
Funnel Chart → CinemaScore Distribution
🎛️ Interactivity
Movie Slicer → Filter by film
People Slicer → Filter by contributors
Dynamic Role Card → Displays selected person’s role
📌 Key Insights
📈 Strong box office peaks in multiple years (>$1B films)
📉 Pandemic caused temporary revenue decline
💰 High-budget films generally perform well
⭐ Majority films rated A CinemaScore → strong audience satisfaction
🎬 Adventure dominates Pixar’s genre strategy
👨‍👩‍👧 Strong focus on family-friendly content (G & PG ratings)
🖼️ Dashboard Preview
<img width="1002" height="570" alt="image" src="https://github.com/user-attachments/assets/c89ea967-0182-4186-9af9-824ad3bc6452" />


/images/dashboard.png

🚀 Tools & Technologies
Power BI
Power Query
DAX (Data Analysis Expressions)

🧠 Learnings
Real-world data cleaning & transformation
Building star schema models
Writing DAX measures & calculated columns
Designing interactive dashboards
Extracting business insights from data

📌 Conclusion

This project demonstrates how Power BI can transform raw datasets into meaningful business insights.

It highlights Pixar’s:

Consistent audience success
Strong storytelling strategy


![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Power Query](https://img.shields.io/badge/ETL-Power%20Query-green)
![Data Modeling](https://img.shields.io/badge/Concept-Star%20Schema-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Dataset](https://img.shields.io/badge/Data-Kaggle-blueviolet)
![Domain](https://img.shields.io/badge/Domain-Entertainment-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
Financial performance trends
