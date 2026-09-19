---
title: "Letterboxd Recommendation System"
excerpt: "Movie recommendation system comparing matrix factorization and sentiment analysis approaches."
collection: portfolio
date: 2024-12-05
---

I completed a semester-long project developing a movie recommendation system for Letterboxd, a social platform for film enthusiasts.

The project explored three approaches to generating recommendations: Singular Value Decomposition (SVD), Non-Negative Matrix Factorization (NMF), and Bayesian Personalized Ranking (BPR). SVD and NMF use matrix factorization to model explicit feedback such as ratings, while BPR is designed for implicit feedback such as whether a user has watched a movie.

The project also incorporated sentiment analysis of user reviews to investigate whether review sentiment could improve recommendation accuracy. The final approach combined matrix factorization predictions with sentiment analysis using a weighted approach, with the parameter β controlling the relative contribution of each method.

Performance was evaluated using Precision@k, Reciprocal Rank, and Normalized Discounted Cumulative Gain (NDCG).

### Project Materials

[View GitHub Repository](https://github.com/sierramk1/Letterboxd-Recommendation-System)

[View Project Slides](/files/letterboxd-slides.pdf)

**Tools:** Python, SVD, NMF, BPR, sentiment analysis