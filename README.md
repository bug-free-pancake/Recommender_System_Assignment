# MovieLens Recommender System Project

## Overview

This project was completed for the course **Analysis of Customer Data**.  
The objective was to analyze customer rating data from the MovieLens dataset and build recommender system models to compare against a baseline.

The project includes two key components:
1. Data exploration and descriptive analysis
2. Development, tuning, and evaluation of recommender models

All work was implemented in Python using the **[SurPRISE](http://surpriselib.com/)** package.


## Dataset

We used the **MovieLens-Ratings.csv** dataset, which contains:
- `userId`: Unique user identifier
- `movieId`: Unique movie identifier
- `rating`: Explicit movie rating (0.5 to 5.0)
- `timestamp`: Seconds since Jan 1, 1970 (not used in the model)

The dataset includes over 27 million ratings and was pre-sorted by `userId` and `movieId`.

# Contribution
My contribution includes data distribution by timestamp in Part 1, matrix factorization-based method and model comparison in Part 2.
