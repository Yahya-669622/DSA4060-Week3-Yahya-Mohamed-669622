# DSA 4060 – Week 3 Practical Lab: Content-Based Recommender System

## Project Overview
This repository contains a simple content-based recommendation system built using structured item features, explicit user preference modeling, weighted feature vectors, and dot-product similarity ranking.

## Repository Structure
- `content_based_lab.ipynb`: Jupyter notebook containing the full implementation, interpretations, and user evaluations.
- `movies.csv`: Structured dataset containing candidate movies and binary genre metadata features.
- `README.md`: Project summary and execution documentation.

## Lab Workflow
1. **Item Feature Matrix**: Structured binary encoding across 5 core genres (Action, Comedy, Drama, Romance, SciFi).
2. **User Preference Vector**: User ratings are used to weight item vectors, aggregating into a normalized user profile.
3. **Recommendation Engine**: Candidate movies are scored via feature dot-product, filtered to exclude watched titles, and ranked.

## Tools Used
- Python 3
- pandas
