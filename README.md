Power BI Twitter Analytics Project (Single Dashboard Version)
Overview

This version of the Twitter Analytics project presents 6 analytical tasks documented separately and all dashboards combined into a single Power BI (.pbix) file. The project focuses on applying strict business rules, advanced DAX calculations, time-based visibility control, and analytical validation using Power BI.

The solution demonstrates real-world analytics scenarios where visuals may partially render or remain blank due to data constraints, ensuring analytical correctness over forced results.

Project Structure
Twitter-Analytics-Power-BI/
│
├── Task 1.docx
├── Task 2.docx
├── Task 3.docx
├── Task 4.docx
├── Task 5.docx
├── Task 6.docx
│
├── twitter.pbix   (All task dashboards in one file)
│
└── README.md

Tools Used

Power BI (DAX, data modeling, visuals)

Excel / CSV (data preparation)

Time intelligence & text preprocessing

Task Summary & Files
Task 1: Media Views vs Media Engagements

Visual Used: Scatter Chart

Objective: Analyze the relationship between media views and media engagements for tweets meeting strict reply, time, date, engagement rate, and word count conditions.

Key Observation: No data points appear due to dataset limitations after applying all constraints.

Files:

Task 1 Explanation

Task 2: Click Interaction Breakdown by Tweet Category

Visual Used: Clustered Bar Chart

Objective: Compare URL clicks, profile clicks, and hashtag clicks across tweet categories under specific time, date, and word count conditions.

Key Observation: Visualization becomes blank when all conditions are enforced, confirming correct DAX logic.

Files:

Task 2 Explanation

Task 3: Top Tweets by Likes and Retweets

Visual Used: Clustered Bar Chart

Objective: Identify top tweets based on combined likes and retweets while excluding weekends and enforcing multiple parity rules.

Key Observation: Fewer than 10 records qualify, reflecting dataset constraints rather than modeling errors.

Files:

Task 3 Explanation

Task 4: Monthly Engagement Rate Trend (Media vs Non-Media)

Visual Used: Line Chart

Objective: Compare monthly average engagement trends for tweets with and without media under strict content, time, and engagement rules.

Key Observation: Missing months indicate periods with no qualifying data, validating correct filter implementation.

Files:

Task 4 Explanation

Task 5: Engagement Comparison Above Median Media Engagement

Visual Used: Clustered Column Chart

Objective: Compare replies, retweets, and likes for tweets exceeding median media engagement within a specific date range and time window.

Key Observation: No qualifying tweets meet all constraints simultaneously, resulting in a blank visual.

Files:

Task 5 Explanation

Task 6: Engagement Rate – App Opens vs No App Opens

Visual Used: Clustered Column Chart

Objective: Compare engagement rates for tweets with app opens versus without app opens under weekday, time, parity, and text conditions.

Key Observation: Only one bar appears due to the absence of qualifying tweets with app opens.

Files:

Task 6 Explanation

Power BI Dashboard

Single Dashboard File:

Complete Power BI Dashboard

Contains all visuals corresponding to Tasks 1–6

Visuals dynamically appear or hide based on defined IST time windows and business rules

Key Analytical Highlights

Advanced DAX feature engineering

Time-based visual visibility control

Text preprocessing and character validation

Odd/even parity checks on dates and metrics

Median-based analytical filtering

Honest handling of real-world data limitations

Author

Abhinay P
Domain: Data Analyst
Project: Power BI Twitter Analytics
