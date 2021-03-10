# A Visual Exploration of Movie Profit Trends

* By Charlotte Basch with Rachel Beery 


#  Introduction

Before the events of the Coronavirus pandemic, the film industry was a tremendously profitable business. In 2019, global box office revenue reached 42.5 billion dollars. In this project we explored data about movie production from 2010 to 2018 using pandas to work with datasets and make visualizations. This project contains data we were given for the module one project in order to make recommendations to Microsoft if they were considering going into the movie business. We were provided with datasets from IMDB, TMDb, and The Numbers which we cleaned and joined. These datasets provided information on movie titles, years, runtime, genres, budgets, profits, and other related variables. The data also contained audience ratings. We focused on three questions about what factors are related to film grosses.

# Questions:
- Do IMDB user ratings relate to profit or budget?
- What genres are the most profitable?
- Does runtime affect movie gross?

## Do IMDB user ratings relate to profit or budget?

![correlations between ratings and monetary variables](https://github.com/charlottebasch/A-Visual-Exploration-of-Movie-Profit-Trends/blob/master/Images/imdb_corrs.png)

When examining the relationship between average IMDB ratings and both budget and gross, there was not a strong correlation, indicating that these opt-in ratings do not represent the general public's tendency to spend money going to see a movie. 


## What genres are the most profitable?

![median gross by genre](https://github.com/charlottebasch/A-Visual-Exploration-of-Movie-Profit-Trends/blob/master/Images/genre_med_gross.png)

It is clear that action, adventure, sci-fi, and animation have the highest median grosses both domestically and internationally. This is further explored in the notebook.

## Does runtime affect movie gross?

![worldwide gross by runtime](https://github.com/charlottebasch/A-Visual-Exploration-of-Movie-Profit-Trends/blob/master/Images/gross_runtime.png)

There does not appear to be much of a relationship between runtime and gross.


# Conclusion

- Online rating should not be used when making decisions about budget or to predict profit. 
- Action, animation, sci-fi, and adventure movies are the most profitable genres. However smaller grossing genres still make a lot of profit. Additionally, many of these genres overlap so the profits observed are not completely additive. 
- Runtime is not related to movie gross unless it is unusually short. 

The movie business continues to expand and by examining the data and isolating the relevant factors, Microsoft would be able to maximize their profits in this kind of endeavor. However this is a simplistic approach that did not consider the role of franchises, prominent actors or directors, whether the movie is based on a popular source material, and other such considerations. Additional types of data could be found and more rigorous analysis could be applied. This also sidesteps the important questions about how movies will be released and make money in a post-pandemic world. The entertainment business as a whole is in flux and it will require time to see how the social, economic, and legal realities of COVID-19 impact moviemaking.