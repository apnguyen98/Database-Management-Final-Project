# Database-Management-Final-Project
# Sorting Amazon Kindle Reviews

## Type of Project:
Restructure a flattened and/or denormalized dataset so it can be loaded into a SQL or Graph database. 
Identify and demonstrate a form of analysis that is made easier by restructuring the data.

## Team Member:
Anh Nguyen: @apnguyen98

## Dataset:
+ File format: JSON
+ File size: 827.8 MB
+ Data Source: Kaggle (https://www.kaggle.com/datasets/bharadwaj6/kindle-reviews/data)


## Introduction

This project aims to restructure this JSON dataset by extracting it to a Python Notebook using SQLite database library in Python and joining the extracted values with the original table. I first pre-processed and cleaned the data using SQL queries by handling missing values, removing duplicates and converting data types, in order to make the data easier to work with. Then, using this new dataframe from the table, I conducted some basic exploratory data analyses such as summarizing its descriptive statistics and visualizing the data to gain insights and identify patterns and correlations within the dataset. 

Next, I explored the distribution of review ratings to understand the overall satisfaction level of customers. I divided the reviews to positive reviews (4 or 5 stars), neutral reviews (2-3 stars) and negative reviews (0 or 1 star) to study the rating distribution on Kindle and how the customers’ satisfaction level is distributed on Kindle.

Last but not least, I utilized thhe Natural Language Toolkit (nltk) library in Python to conduct a sentiment analysis on the actual text reviews of the dataset. By doing so, I can classify reviews as positive, negative, or neutral and study their distribution within existing reviews.


