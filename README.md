# Netflix-Movie-Data-analysis-

# INTRODUCTION

Based on the massive movie information available on the internet, it would be fascinating to learn
what aspects contribute to a film's success and determine how uniform or polarized the opinion of a movie is.
It's always been fun to experiment with the combination of user ratings for movies and detailed movie
metadata. As a result, we'd like to investigate which types of films are more popular or have a higher IMDB
rating. We also wish to illustrate the study's findings to make them more intuitive. The response variable in
this study is IMDB rating, while the rest of the components in the IMDB movie dataset are analyzed to focus
on operating predictions.
We will be exploring the IMDB Movies Datasets taken from https://www.kaggle.com/.

# STATEMENT OF GOALS

Through a series of plots and inferences, we want to investigate the findings of the following questions:
1. Relationship between the length of a movie(runtime) and its rating on IMDB.
2. Relationship between the count of votes and ratings.
3. Relationship between rating and movies across all years.
4. Are the highest-rated movies the ones with the most votes?
5. Do the movie genres have an impact on ratings?
6. Does language have an impact on movie ratings?
7. Does a top successful director affect the movie ratings?

# DATA DESCRIPTION
This dataset contains 14 columns for 8451 shows from various countries spanned across 89 years between
1916 and 2005. When we first looked at the Dataset, we noticed that only 4 of the columns contained numerical
values, while the rest were categorical, meaning that the data for those columns was stored in a labeled manner.
The description of the variables in the dataset is as follows:


Categorical Variables:
● Title: describes name of the show
● Year: the year in which the movie/show was released
● Kind: kind of TV show i.e., tv mini series, movie, episode
● Genre: refers to the type of story being told and is decided by the playwright
● Country: Countries In Which The Shows Were Released
● Language: describes in which language the show was shot
● Cast: the group of actors who acted in the show
● Director: director of the show
● Writer: person who writes the scripts
● Composer: names of music director


# DATA CLEANING:

We deleted outliers (97 quartile runtime values) that could potentially skew the distribution in this dataset
by removing redundant information such as observations with numerical null values. While analyzing the
data, we encountered unrealistic and false runtime for some movies. These movies have a very large
runtime. We considered them as outliers and removed them. For the sake of this study, we solely looked at
movies.
These values depict the number of N/A values in that particular column. The variables ‘runtime’, ‘rating’
and ‘vote’ have 1653, 316 and 316 null values respectively which were removed from the data.

# CONCLUSION:

1. If the runtime of the movie is outside the range 90 to 120 minutes then the ratings are most
likely to decrease.
2. As the count of the votes increases for a movie the ratings also tend to be higher.
3. The average IMDB ratings for the movies have decreased over the years.
4. The movies with the highest ratings tend to have the highest number of votes. Example: “The
Shawshank Redemption”.
5. The genre does affect the ratings and the documentary genre seems to have the highest rating
when compared to others and SD explains that the variation in voter ratings differ from genre to
genre.
6. The different movie languages have different average ratings. But French movies tend to have
the highest rating and English movies have a large variation since it has the highest movie
count.
7. A successful director does affect the number of votes received and ratings achieved. We found
that “Frank Darabont” is the top most successful director and his movie “The Shawshank
Redemption” received the highest votes and ratings till today.
LIMITATIONS:
