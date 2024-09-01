![Recommendation Dashboard](https://github.com/xChrisMo/IBM_Recommendation_Engine/blob/main/Screenshot%202024-09-01%20at%2018.53.02.png)

# IBM Recommendation Dashboard

## Project Overview

This project's goal is to analyze the interactions that users have had with articles on the IBM Watson Studio platform and recommend new articles they might like.

## Program Structure

In this project, I explored four recommendation systems on real data for the IBM Watson Studio platform:

1. Rank Based Recommendation.
2. User-User Based Collaborative Filtering.
3. Content Based Recommendations(using NLP)
4. Matrix Factorization.

## Executive Summary

* Ranked Based Engine - recommending based on popularity
* Collaborative Engine - recommending data based on similar data between different users
* Content Based Engine - using NLP to extract keywords to predict similarly
* Matrix Factorization Engine - recommending based on hidden features of articles provided by a Machine Learning Algorithm

## Libraries Used
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [nltk](https://www.nltk.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
  

## Files in the Repository
- `user-item-interactions.csv`: File containing user interaction.
- `articles_community.csv`: File containing articles description.

## How to Use
1. Clone this repository
2. Ensure you have all the required libraries installed
3. Open the `Recommendations_with_IBM.ipynb` notebook in Jupyter or your preferred environment
4. Run the cells to reproduce the analysis

## Acknowledgments
Thanking [udacity](https://www.udacity.com/dashboard) for this amazing project, and [IBM Studios](https://www.ibm.com/uk-en) for providing the data.

## Licensing 
Copyright (c) 2024, Ayo

This project is for personal and educational purposes only. All rights reserved.
