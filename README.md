# Twitter-Sentiment-Analysis

Twitter Sentiment Analysis & Trend Detection using PySpark and Flask
Summary

This project illustrates a comprehensive big data analytics and machine learning workflow for examining tweets. Employing the PySpark API from Apache Spark for distributed computation alongside Flask for the web interface, the system carries out sentiment analysis and hashtag trend identification on extensive Twitter datasets.

The solution encompasses every phase of a large data workflow — including data ingestion and cleansing, feature engineering, model training, and interactive visualization.


Goals:

Create a scalable analytics pipeline for processing Twitter big data.

Categorize tweets based on sentiments (positive, negative, neutral) or classifications.

Identify and illustrate hashtag trends throughout time.

Incorporate findings into an interactive dashboard built on Flask.


Architectural Design:

Data Ingestion – Import twitter.csv into Spark DataFrames while inferring the schema.

Data Cleaning – Eliminate null entries, URLs, mentions, special characters; transform timestamps.

Feature Engineering – Derive word counts, sentiment metrics; transform categorical variables; integrate features through VectorAssembler.

Data Division – Train/test separation (70/30) utilizing Spark’s randomSplit.

Machine Learning Algorithms – Train Logistic Regression and Decision Tree Classifier using Spark MLlib.

Assessment – Utilize accuracy, precision, recall, F1-score, and confusion matrix.

Visualization – Create sentiment distributions, word clouds, hashtag trends.

Deployment – Flask interface for sentiment analysis and trend investigation
