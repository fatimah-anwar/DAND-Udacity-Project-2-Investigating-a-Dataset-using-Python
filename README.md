# Udacity Data Analyst Nanodegree Project: 
# Investigating a Dataset (TMDb Movie Data) using Python 

In this project, I go through the data analysis process to investigate a dataset and communicate my findings about it using Python libraries NumPy, pandas, and Matplotlib. The analyzed dataset is TMDb Movie Data which contains information about 10,000 movies collected from The Movie Database (TMDb).

## Files:
- tmdb-movies.csv

## Questions to Answer:

- How do the number of movies in each genre change over time?
- Is there a relationship between user average votes and movies revenues?
- What runtime is associated with movies that have high revenues?
- What is the best release (month / week / day of week) that guarantees high movie revenues?

## Findings:

In the process of producing and releasing a new movie, production companies must take into consideration four main factors:

1. **Movie's Runtime:** Producing a movie with runtime between 2 to 2 and a half hours will likely maximize the revenue to the highest possible amount, while a runtime bellow 1 hour or above 3 and half hours will bring the lowest revenue. 


2. **User Average Votes:** There is a strong relationship between user average votes and movies revenue in which higher average votes leads to higher revenue. So, the production companies must focus on meeting the users expectations to guarantee high average votes in order to maximize their revenue


3. **Release Date:** The date in which a movie is released in could strongly affect the revenue, and from the analysis we can conclude that June and December are considered the best months for releasing a movie that guarantees the highest revenue, and the third week of a month and both Friday and Wednesday are considered the best week of the month and day of the week respectively. So if a production company wants to maximize its revenue as much as possible, it must select the release date wisely. 


4. **Competition Nature in The Produced Movie Genre:** The proportion of producing Animation, Documentary, Horror, Music, Science Fiction, Thriller, and TV movies is increasing over the years, while the proportion of producing Action, Adventure, Comedy, Crime, Family, Fantasy, History, Romance, war and western movies is decreasing. And the proportions of Drama and Mystery movies are almost consistent. In addition to the fact that Drama movies productions are the highest over the years followed by Comedy and Thriller, then Action and the rest of the genres. So, when selecting the genre of the next movie to be produced, a production company must be aware of the competition nature in the selected genre. 
