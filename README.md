# Consulting_Fidelity
Topic Modeling Project

Overview

This topic modeling project analyzes IMDB Movie Review dataset (50000 reviews) from Kaggle collected by Standford. The IMDB dataset contains movie reviews along with their associated binary sentiment polarity labels. It is intended to serve as a benchmark for sentiment classification. But in our analysis, we focus more on topic identification instead of sentiment analysis, so we don't split these reviews for cross validation.

Dataset

Reference: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

The core dataset contains 50,000 reviews split evenly into 25k train and 25k test sets. The overall distribution of labels is balanced (25k pos and 25k neg). In the entire collection, no more than 30 reviews are allowed for any given movie because reviews for the same movie tend to have correlated ratings.

Contribution

Jiaqi Sun: custom stop-word, sentiment analysis, n-grams and correlation, LDA <br>
Yaquan Yang: n-grams and visualisation for negative, positive remarks <br>
Hao He: CAPS effect on sentiment analysis, stemming and lemmatization, LDA <br>
Huifei Xu: polarity & visualiztion for Sentiment Analysis; topics exploration Sec.7; Miscellaneous details handling <br>
All members collaborate on the report generation.

Running time issue

1. When we use qdap package to plot the polarity of IMDB reviews, the running time range from 1 to 2 hours depending on the computer's CPU.











