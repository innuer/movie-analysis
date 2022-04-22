# movie-analysis

# Contributors 
1. Tay Jia Yi
2. Sebastian Palanca

# Introduction
This is a mini-project for SC1015 which focus on movies from movie data set. 
1. Problem: Predicting Gross Revenue of a film based on certain variables. 
2. Dataset by: Kasidis Satamongkol.
3. Motivation: Interest in movies, optimizing production decisions to maximize Gross Profit.

# Main variablea that were focus on 
1. IMDb score 
2. Budget
3. Lead actor Facebook Likes
4. Director Facebook Likes 
5. Genre
6. Gross Revenue 

# Initial insight 
1. Budget has the highest correlation with gross revenue 

# Cleaning of data set
1. Movies not from 'USA' removed.
2. Genres that have less than 100 entries removed. 
3. Released Date before 2004 removed.

# Models used
1. Multivariate Linear Regression
2. Decision Tree Regression 
3. Random Tree Regression 
4. K-Nearest Neighbors 

# Conclusion 
1. Both Lead actor and director Facebook likes have poor correlation with gross revenue. 
2. Budget on adventure movies might have the most potential to maximize the gross Gross Revenue.
3. Decision Tree Regression had the lowest accuracy
4. K Nearest Neighbors had the highest accuracy score but its doesn’t make it an excellent predictor.

# What did we learnt from this project?
1. Random decision tree and K-Nearest Neighbors 
2. The extreme variability of the data set outlines perhaps the need for more metrics, and a more detailed exploration into other factors like Age Ratings, Country, or even other social media metrics, like those of their trailers, or twitter visibility.
3. Budget is definitely a massive factor



