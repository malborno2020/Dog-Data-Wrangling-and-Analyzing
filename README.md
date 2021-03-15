# Dog-Data-Wrangling-and-Analyzing
This a data wrangling and analysis exercise part of a Udacity Data Analytics course

## Introduction

This project entails the wrangling and data analysis contained in three separated datasets all with a common origin in a Twitter dog rating platform called WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. This project is an assignment from UDACITY Data Analytics course.

## Getting started

Please make sure you install and import all relevant packages before you give it a go!

$ conda install -c conda-forge tweepy

%matplotlib inline

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

import requests

import tweepy

from tweepy import OAuthHandler

import json

from timeit import default_timer as timer

## Usage

Three datasets are used in this project need to be available in the same working directory:

    An Enhanced Twitter Archive twitter-archive-enhanced.csv extracted and enriched by Udacity to use in this project containing tweet data (tweet ID, timestamp, text, etc.) for over 2500+ of tweets between August 1, 2015 and August 1, 2017.

    An Image Predictions Dataset image-predictions.tsv' with images of the dogs and their respective breeds obtained through a neural network containing URL images and tweet_id.

    An Additional Twitter Dataset to be gathered from Twitter's API using the tweet_id contained in the Enhanced Archive. 
    
The code to interrogate the API and the ouput file 'tweet-json.txt' are provided in case you don´t want to retrieve the data yourself.

## Need help?

Drop an e-mail manuel.albornoz@zoho.com
