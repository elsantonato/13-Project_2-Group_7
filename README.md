# Project-2: The Numbers
Data Analytics Boot Camp, Group Project 2: ETL (Extract Transform Load)

## Group 7 Movies Database 
Members: Lisa Santonato, Minna Wu, Dian Wang, Suchitra Sharma
 
### Abstract
The project’s objective was to compare film box office revenue with user and critic ratings.  To conduct this comparative research, data was first extracted from multiple sources and then compiled into a central database. We extracted gross earnings from the-numbers.com, determining which films were the top-grossing releases for that week, noting the producing companies and distributors behind them. We then extracted user and critic ratings for the top 100 films of all time, scraping data across multiple sources to illustrate the comparison between critic and user scores. 

### Next steps
The ratings and revenue data can be triangulated together to draw comparative inferences to identify whether any correlations can be drawn between box office revenue and audience scores.  

### Research Questions
* What are the top grossing films per week? 
* What are the top 100 grossing films of all time?
* What are the ratings of these top 100 grossing films on Metacritic.com, IMDB.com, and RottenTomatoes.com?
* What does the comparison between critic scores and user scores look like?
* What correlations, if any, can be drawn between critic and user scores, and box office revenue? 
 
### Breakdown of Roles and Tasks
The ETL process is composed of Extract, Transform, and Load subprocesses. Breakdown of roles and tasks are detailed below under each subprocess.

#### Extract
* Lisa: Scrape the-numbers.com for top 100 grossing movies for the week
*	Minna: Scrape web tables from the-numbers.com for top 100 grossing movies of all time as the base data
*	Minna: Scrape Metacritic.com for user vs. critic ratings and other movie details
*	WangDian: Scrape Rotten Tomatoes for user vs. critic ratings and other movie details
*	Sue: OMDB API to scrape IMDB ratings

#### Transform
* All members will be using Pandas to clean the data
* Minna: Final cleaning and merging into one table using Pandas

#### Load
* Minna: Load into MongoDB the compiled tables from each website as well as a composite table containing all data

#### Plots
- Lisa: Profit by Year for Top 100 Grossing and other related analyses
- WangDian: Top 10 By User Score (IMDB, RottenTomatoes, Metacritic, and overall)
- WangDian: Top 10 By Critic Score (RottenTomatoes and Metacritic, and overall)
- WangDian: User vs. Critic Score for Top 10 Movies for 
    * Top 10 Movies where users like the movie more than the critics
    * Top 10 Movies where critics like the movie more than the users

### Analysis
Please see our [Jupyter Notebook](./final.ipynb) and our [Final Report document](./FinalProjectReport.docx).
