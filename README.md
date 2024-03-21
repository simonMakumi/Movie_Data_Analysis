# Introduction
Microsoft aims to venture into the film industry by establishing a new movie studio. However, lacking expertise in movie production, they seek insights into successful film genres at the box office. This analysis aims to explore the current landscape of box office success and translate findings into actionable insights for Microsoft's movie studio.
## Business Understanding

## Stakeholder: Microsoft's new movie studio

### Key Business Questions:

* What types of films are currently performing well at the box office?
* How can these findings inform decisions regarding the types of films to produce?
* What genres are most popular among audiences?
* How do factors like production budget and ratings influence a film's success?
* Who are the top writers and producers?

### Data Understanding and Analysis

### Data Sources:

####  tn.movie_budgets.csv:

##### Used to get:
*Production Budget Statistics.
* Domestic Gross Earnings Statistics.
* Worldwide Gross Earnings Statistics.
* Correlation analysis.
#### bom.movie_gross.csv:

##### Utilized for:
* Analyzing the Distribution of Domestic and Foreign Gross Earnings Over the Years.
* Identifying top movies by gross earnings.
#### tmdb.movies.csv:

* Explored for Distribution of Movies by Original Language.
#### im.db:

##### Merged tables (movie_basics, movie_ratings, movie_akas) for analyzing:
* Top 10 produced genres.
* Average rating of each genre.
* Top 20 genres with the highest average rating.
* Correlation between movie rating and votes.

#### Visualizations:
* Production Budget vs. Worldwide Gross Earnings (Correlation analysis)
* Distribution of Domestic Gross Earnings Over the Years
* Distribution of Foreign Gross Earnings Over the Years
* Top movies by Domestic and Foreign Gross (Boxplots)
* Distribution of Movies by Original Language (Count plot)
* Top 10 produced genres (Bar graph)
* Top 20 genres with highest average rating (Bar graph)
* Correlation between movie rating and votes (Scatter plot)

### Main Conclusions:

* English is the predominant language in movies.
* Domestic Gross Earnings show an increasing trend over the years.
* Foreign Gross Earnings exhibit significant variability.
* Some of the most produced genres include Drama, Documentary, Comedy, etc.
* Top 5 Genres with Highest Average Rating vary from Comedy to Documentary and Musical.
* There is no significant correlation between movie rating and votes.
* The directors with most movies in Comedy, Documentary and Drama are A. Blaine Miller, A. Branham Dyer and 'Atlas' Ramachandran respectively.
* The writers with most movies in Comedy, Documentary, Drama are 'Om' Rakesh Chaturvedi, A. Branham Dyer, A Rahman respectively.
