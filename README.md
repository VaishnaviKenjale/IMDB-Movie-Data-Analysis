# IMDB-Movie-Data-Analysis

![image](https://github.com/user-attachments/assets/538f1201-868f-4c93-a4ce-cdf7ac1d1683)

IMDB Movie dataset analyze using pandas library in python and also visualize data using matplotlib and seaborn library.

# Introduction
The IMDB Movie Dataset contains information on 1,000 of the most popular movies during this period. The dataset includes various attributes such as the movie title, genre, description, director, actors, release year, runtime, IMDB rating, number of votes, revenue, and metascore.

# Objective
The objective of this analysis is to uncover patterns, trends, and insights from the data, which could help in understanding what factors contribute to a movie's success and popularity.

# Data Exploration
Before diving into detailed analysis, an initial exploration of the dataset was conducted:
1. Dataset Overview: The dataset consists of 1,000 movies with 12 columns. Each row represents a unique movie, and the columns contain various attributes about the movie, such as genre, rating, and revenue.
2. Missing Values: The dataset contained some missing values in critical columns like revenue and metascore. These were handled by dropping rows with missing data, ensuring the analysis is based on complete information.
3. Duplicates: A check for duplicate entries was performed, and any duplicates found were removed to avoid skewing the analysis.
4. Statistical Summary: Basic descriptive statistics were generated for numerical columns like runtime, rating, votes, revenue, and metascore to understand their distribution and central tendencies.

# Key Findings

The analysis was structured around several key questions:

1. Trends in Movie Ratings Over the Years:
Movies released between 2006 and 2016 generally maintained high IMDB ratings, with slight fluctuations. No significant downward or upward trends were observed in ratings over time, suggesting a consistent quality of popular movies.

2. Relationship Between Runtime and Ratings:
A moderate correlation was observed between the runtime of movies and their IMDB ratings. Generally, movies with longer runtimes tended to have slightly higher ratings, possibly indicating that more complex, detailed stories are appreciated by viewers.

3. Revenue Distribution and Its Correlation with Ratings:
The analysis revealed a positive correlation between movie ratings and revenue. Generally, movies with higher ratings tended to generate higher revenue. This suggests that higher-quality movies, as reflected by their ratings, are more likely to achieve commercial success.

4. Analysis of Genres and Their Popularity:
The genre analysis revealed that certain genres, such as Action, Drama, and Adventure, were more prevalent among popular movies. However, no single genre consistently outperformed others in terms of ratings, indicating that a wide variety of genres resonate with audiences.

5. Impact of Directors on Movie Ratings:
Christopher Nolan's movie achieved a high rating of 8.68, highlighting the significant impact of a renowned director on a film's success.

6. Top 5 Highest Revenue Movies are:
      Movies with Revenue :
         1] Star Wars: Episode VII - The Force Awakens 936.63
         2] Avatar 760.51
         3] Jurassic World 652.18
         4] The Avengers 623.28
         5] The Dark Knight 533.32

7. Most of the people loves Drama, Adventure, Action and Comedy movies.

# Conclusion
This analysis of the IMDB Movie Dataset from 2006 to 2016 provides several insights into the dynamics of popular movies. Movies directed by well-known directors, such as Christopher Nolan, tend to receive higher ratings, as evidenced by Nolan's movie achieving a rating of 8.68. Additionally, movies with higher ratings generally generate higher revenue, underscoring the importance of quality in commercial success. Revenue does not necessarily correlate with higher ratings, indicating that commercial success involves factors  beyond just the quality of the movie. Finally, the variety in genres among popular movies suggests that audience preferences are diverse, and successis not confined to a specific genre.

