# Project-2
Data Analytics Boot Camp Group Project 2: ETL (Extract Transform Load)

## Group 7 Movies Database 
Members: Lisa Santonato, Minna Wu, Dian Wang, Suchitra Sharma
 
### Abstract
The objective of this project is to extract data from multiple sources of online movie ratings and compile them into a central database. Using this database, one can conveniently compare user and critic ratings across multiple sources (i.e. IMDB, RottenTomatoes, and Metacritic). Our process involves extracting the Movie earnings and rating data from our sources, transforming it into a format for merging, and then loading it to MySQL workbench. The project aims to answer several possible questions as outlined below.

### Research Questions
* What are the top grossing films per week? 
* What are the rankings on Metacritic.com, IMDB.com, and RottenTomatoes.com?
* How do the film rankings differ between websites? 
* What does the comparison between critic scores and user scores look like?
 
### Breakdown of Roles and Tasks
The ETL process is composed of Extract, Transform, and Load subprocesses. Breakdown of roles and tasks are detailed below under each subprocess.

#### Extract
* Lisa: Scrape the-numbers.com for top 100 grossing movies as the base data
* WangDian: Scrape Rotten Tomatoes for user vs. critic ratings
* Sue: Download IMDB CSV with ratings and use movie IDs to find titles in IMDB API
* Minna: Scrape Metacritic for user vs. critic ratings

#### Transform
* All members will be using Pandas to clean the data
* Minna: Final cleaning and merging into one table using Pandas

#### Load
* Minna: Load into MongoDB with tables from each website as well as a merged table

#### Plots
- Lisa: Profit by Year for Top 100 Grossing and other related analyses
- WangDian: Top 10 By User Score (IMDB, RottenTomatoes, and Metacritic, overall)
- WangDian: Top 10 By Critic Score (RottenTomatoes and Metacritic, overall)
- WangDian: User vs. Critic Score for Top 10 Movies for 
    * Top 10 Movies where users like the movie more than the critics
    * Top 10 Movies where critics like the movie more than the users

### Analysis
Please see our [Jupyter Notebook](./final.ipynb) and our [Final Report document](./FinalProjectReport.docx).
