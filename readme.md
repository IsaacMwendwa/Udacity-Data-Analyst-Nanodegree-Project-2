
# Udacity Data Analyst Nanodegree Project 2: Data Wrangling

### by Isaac Mwendwa

## Introduction
* This repository contains the full code, datasets and the report for the Data Wrangling process I undertook in Project 2 of the Udacity Data Analyst Nanodegree
* The Data Wrangling Project I undertook revolves around the Twitter Account "WeRateDogs", an account for rating dogs based on their various features.

* This readme will be formatted into 3 sections (following the 3 steps of the Data Wrangling Process):
> * Gathering Data
> * Assessing Data
> * Cleaning Data


## Part 1: Gathering Data
The initial step in the data wrangling process entails collecting the data required for the project. This project uses three datasets:
* **twitter_archive_enhanced.csv** – the WeRateDogs Twitter Archive dataset, which is readily provided for manual download.
After downloading the dataset, I uploaded it to the Project Workspace and read the data into a Pandas dataframe.
* **image_predictions.tsv** – a file containing dog image predictions, created using a neural network. I downloaded the file
programmatically from the Udacity’s servers using the Requests library.
* **tweet_json.txt** – a file containing data gathered from the Twitter API. I queried the Twitter API for additional information (e.g.,
retweet count, favorite count) using the tweet IDs in the WeRateDogs Twitter archive, and stored the data in the file tweet_json.txt

I then read the data in the three datasets into three separate dataframes;
one for each dataset – in readiness for Step 2 of the Project.
