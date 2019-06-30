# Explore movies data from The Movie Database (TMDb)
## by Anh Le


## Dataset
> This report analyses "tmdb-movies" dataset which contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. The movie industry is exciting as it's full of surprises. A movie can bring back millions dollar of profit. This report studies the following 2 questions.
1) Which genres are most popular thorough the years?
2) What kinds of properties are associated with movies that have high revenues?

Source: https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv

## Summary of Findings
> This report focus on 2 questions:
1) Which genres are most popular thorough the years? The popularity of all the genres thorough the years has been analysed, and the following genres are most popular:

- Action
- Adventure
- Fantasy
- Science Fiction
- Western

2) What kinds of properties are associated with movies that have high revenues?

vote_average: the association with high revenue is quite weak. However it's worth noting that the high revenue movies have high vote_average, while the high vote_average doesn't guarantee high revenue
genres, director, cast and production_companies: these features are associated with high movie revenues. There are genres, directors, actors and production companies have high counts of high revenue movies, while some genres, directors, actors and production companies only have 1 high revenue movie.

## Limitation
The analysis of the question #2 is limited due to the bias involved with the imputation was made for both budget_adj and revenue_adj. The imputation, in which means are used, introduced bias as most of these 2 features observations are outliners. However, due to the high percentage of missing data in budget_adj and revenue_adj, and these two features are important, imputation is necessary for them.
