# Exploratory-Analysis-on-Movie-dataset
This was a part of out 6th Semester Mini Project.

Group Members: Akshaya Ramanathan, Ramita Shinde, Rutuja Phatak

Introduction:
The data set we chose is Movie dataset. You can find this dataset easily from kaggle.
-->Here are some notes and comments about this datasets : This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user 
   ratings and revenue.
-->Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
-->There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
-->The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

The questions about this dataset:
1. Does higher budget mean higher popularity ? Is there a coefficent relationship ?
2. Will the runtime affect the vote count and popularity?
3. Higher popularity means higher profits ?
4. Which genres are most popular from year to year?

Conclusion:
Based on the analysis we did, we can make the following summarizations:
1. The quantity and range of movie gets larger.We have more choices to choose from as an audience.
2. We can not say high budget guarantees high popularity. But for movies with higher budgets do produce higher average popularity.
3. To produce a more popular movie, the runtime should be best around 150 mins; Drama, Comedy, Action, these genres would be preferable.

Limitations:
1. These are factors that makes the movies become popular and successful. But we should also notice the limitations. There are some missing data and many erroreous zeros which may affect the analysis.
It's hard for us to know how the vote_counts and popularity are measured.

2. For foreign movies,currecy is not indicated. inflation over the years should also be taken into consideration.

Reference:
1. https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.nlargest.html
2. https://www.kaggle.com/diegoinacio/imdb-genre-based-analysis 
3. https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.apply.html 
4. https://pandas.pydata.org/pandas-docs/stable/visualization.html
