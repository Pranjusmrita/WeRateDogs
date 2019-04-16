# WeRateDogs

### Project Motivation

This project majorly dives into the detailed process involved in Data Wrangling process namely: Data Gathering, Data Assessing and Data Cleaning. The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.

### Pre-requisites

Here, I am working with Python in Jupyter notebook. We would require installing Anaconda which comes handy with all the packages that I have used in this project. Following are the libraries that needs to be installed before getting started with the Jupyter notebook:

1. Numpy
2. Pandas
3. Matplotlib
4. requests
5. tweepy
6. json

Also to query data using twitter's API we need to set up a developer account in Twitter for generating the Consumer API keys, and the Access Token and Access Token Secret that will be needed in this project.

### Project workflow

1. Gathering Data
I have gathered data from three different sources: From a csv file, from a image-predictions file and additional data via Twitter API. I have then queried the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called tweet_json.txt.
2. Assessing Data
After gathering each of the above pieces of data, I have assessed them visually and programmatically for quality and tidiness issues. Here I have documented 8 quality and 2 tidiness issues.
3. Cleaning Data
I have further cleaned the dataset for each of the identified issues and stored the clean dataframe into a csv file.
4. Analyzing and Visualizing Data
The clean dataset has been analyzed and interesting aspects of data have been documented by different visualizations.
