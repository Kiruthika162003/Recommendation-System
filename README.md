# Recommendation Systems with Python Machine Learning AI

## Introduction
This project builds various recommender systems: Classification-based, Model-based Collaborative Filtering systems, and Content-based recommender systems. At the end, we evaluate which recommender performed the best.

## Problem Statement
We aim to develop and compare different types of recommender systems to determine which one provides the most accurate recommendations.

## Results Interpretation
- **Classification-based Collaborative Filtering**: Uses Logistic Regression to predict recommendations.
- **Model-based Collaborative Filtering**: Utilizes SVD Matrix Factorization for recommendations.
- **Content-based Recommender**: Employs Nearest Neighbor Algorithm to recommend items based on content similarity.

## Methodology
1. **Data Collection**: Gathered data from various sources.
2. **Data Preparation**: Cleaned and preprocessed the data for analysis.
3. **Model Building**: Developed different recommender systems.
4. **Evaluation**: Compared the performance of each recommender system.

## Steps Done
1. **Data Loading**: Loaded datasets using pandas.
2. **Data Inspection**: Checked the structure and content of the datasets.
3. **Model Implementation**: Implemented different recommender systems.
4. **Performance Evaluation**: Evaluated the performance of each system to determine the best one.

## Data
- **Bank Marketing Data**: Used for Classification-based Collaborative Filtering. [Link](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#)
- **MovieLens Data**: Used for Model-based Collaborative Filtering. [Link](https://grouplens.org/datasets/movielens/100k/)
- **mtcars Data**: Used for Content-based Recommender. Source: Henderson and Velleman (1981), Building multiple regression models interactively. Biometrics, 37, 391–411.

## Recommender Systems
1. **Classification-based Collaborative Filtering Systems**
   - File: Classification_based_collaborative_filtering.ipynb
   - Demonstrates how classification-based CF works using Logistic Regression.

2. **Model-Based Collaborative Filtering Systems**
   - File: Model-based_collaborative_filtering.ipynb
   - Demonstrates how model-based CF works using SVD Matrix Factorization.

3. **Content-Based Recommender Systems**
   - File: Content_based_recommender_systems.ipynb
   - Demonstrates how content-based recommender system works using Nearest Neighbor Algorithm.
