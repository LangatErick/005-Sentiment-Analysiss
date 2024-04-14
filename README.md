# Project-Sentiment-Analysis
Data Science Project – Sentiment Analysis Project in R

## R Project -- Sentiment Analysis

This project aims to build a sentiment analysis model that will allow us to categorize words based on their sentiments, that is whether they are positive, or negative, and also the magnitude of it. Before we start with our R project, let us understand sentiment analysis in detail.
![image](https://github.com/LangatErick/Project-Sentiment-Analysiss/assets/124883947/8cd68074-fcbf-4f31-a7b9-7458e04ca3a7)


## What is Sentiment Analysis?
Sentiment Analysis is a process of extracting opinions that have different polarities. By polarities, we mean positive, negative, or neutral. It is also known as opinion mining and polarity detection. With the help of sentiment analysis, you can find out the nature of opinion that is reflected in documents, websites, social media feeds, etc. Sentiment Analysis is a type of classification where the data is classified into different classes. These classes can be binary (positive or negative) or have multiple classes (happy, sad, angry, etc.).

## Developing our Sentiment Analysis Model in R

We will carry out sentiment analysis with R in this project. The dataset we will use will be provided by the R package 'janeaustenR'.

To build our project on sentiment analysis, we will use the tidytext package comprising sentiment lexicons present in the dataset of 'sentiments'.
```
#load the libraries
library(bookdown)
suppressPackageStartupMessages(require(tidyverse))
library(tidytext)
#check sentiments
dim(sentiments)
head(sentiments)

````
