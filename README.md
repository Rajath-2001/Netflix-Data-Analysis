# Netflix-Data-Analysis
This project analyzes the Netflix dataset to uncover insights about titles, genres, ratings, countries, directors, and yearly progression of content.

Dataset
Source: netflix_titles.csv

Records: 8,807 titles

Features: Title, Director, Cast, Country, Release Year, Duration, Rating, and Genre.

 Key Insights
 
Total Titles: 8,807 

Countries Represented: 86

Top Genres: Stand-Up Comedy, Documentaries, Dramas, International Movies

Content by Type:

Movies: 69.62%

TV Shows: 30.38%

Average Duration: 99.58 minutes

Top Director: Rajiv Chilaka with 19 titles

Highest Rating Category: TV-MA (3,207 titles)

Visualizations in Dashboard

No. of Titles by Genre – Bubble chart showing most popular genres.

Content by Type – Custom doughnut chart displaying ratio of Movies vs TV Shows.

Created using two AGG(min(0)) measures in Rows, converting one into a circle, and using dual axis.

Yearly Progression – Bar chart showing growth trend of Netflix titles (2008–2021).

Content by Rating – Treemap of ratings (TV-MA, TV-14, PG, etc.).

No. of Titles by Country – World map showing distribution of titles globally.

Tools & Techniques

Tableau for dashboard creation

Data Cleaning:

Used split function to normalize country data

Extracted Telecasted Country for mapping

Custom Charting:

Doughnut chart created manually using dual axis technique

A new column Telecasted Country was created using split function because the original Country column contained multiple values.

Top 10 Directors – Horizontal bar chart highlighting directors with the most titles on Netflix.
