# recommendation-engine-platform
End-to-End Recommendation System using Machine Learning, Deep Learning, Collaborative Filtering, Content-Based Filtering, Explainable AI, MLOps, and Streamlit Deployment.

# Recommendation Engine Platform

## Project Overview

Build an industrial-scale movie recommendation system using MovieLens 32M.

## Dataset
- links.csv
- movies.csv
- ratings.csv
- tags.csv

## Workflow
1. Data Understanding
2. Advanced EDA
3. Feature Engineering
4. Content-Based Filtering
5. Collaborative Filtering
6. Hybrid Recommendation
7. API Development
8. Deployment

### Weighted Rating Feature

Implemented IMDb-style Weighted Rating to improve ranking quality.

Formula:

WR = (v/(v+m) × R) + (m/(v+m) × C)

Where:
- R = Average movie rating
- v = Number of ratings
- C = Mean rating across all movies
- m = 90th percentile of rating counts

This reduces bias from movies with very few ratings and improves recommendation quality.
