# Star Wars: Galaxy's Edge Experience Data Analysis
The goal of this project was to analyze guest feedback (i.e. beliefs, emotions, and sentiments) about Star Wars: Galaxy's Edge and identify new competitive advantages in hidden patterns by better understanding the fans.

Star Wars: Galaxy's Edge is one of the most ambitous and immersive themed experiences ever created. It opened at Disneyland in Anaheim, California on May 31, 2019 and Hollywood Studios at Walt Disney World in Orlando, Florida on August 29, 2019. Each of these 2 themed areas cost an estimated $1 billion and feature over 14 acres of attractions, shops, and restaurants.

## Data Type
There are 2 types of data: operational data and experience data. For this analysis, I used experience data.

### Operational Data
* Tangible records of tangible activities like sales (tickets, merchandise, concessions), finance and HR
* Data about the past
* Tells you what happened

### Experience Data
* Human feedback that points to the gaps between what you think is happening and what’s really happening
* Data about the future
* Tells you why it's happening

## Data Sources
For this analysis, I focused on experience data collected from:
* Online Survey
* Twitter
* Google Trends

## Online Survey Data
I created a survey using Google Forms and collected 165 responses from various Reddit subreddits including: 

* r/StarWars 
* r/WaltDisneyWorld 
* r/disneyparks 
* r/DisneyWorld 
* r/Disneybound 
* r/GalaxiesEdge 
* r/DisneyTravel 
* r/Disneyland

### Age Groups of Survey Participants
Below is a pie chart that visualizes survey participation by age group. Ages 25-34 represent the largest age group who participated in the survey. The next 2 largest age groups are the adjacent youngest and oldest age groups making the largest representation 18-44. The smallest participating age groups are the youngest (18 and under) and the oldest (65 plus).

![Age](images/age.png)

### Experience Ranking by Age Group
Below you'll see the ranked importance of each experience by age group. Across all age groups, the most important experiences are the rides with Rise of the Resistance as #1 and Smugglers Run as #2. After the attraction, the middle three age groups comprising 18-44 were most interested in Ogas Cantina after the attractions while both the youngest and oldest age groups were interested in the shopping experiences primarily Savis and Droid Depot. Den of Antiquities is a popular shopping location across all age groups. Den of Antiquties is like a souvenir shop meets museum.

![Ages Grouped](images/age_grouped.png)
![Ages Seperate](images/age_seperate.png)

### Correlations
Below are the correlations between experiences. The darker the blue, the more likely someone is to be interested in those experiences together. We see that Savis and Droid Depot are both of interest together.

![Corr Matrix](images/corrmatrix.png)

The clustermap groups experiences together for a different view of correlations.

![Clustermap](images/clustermap.png)

## Twitter Sentiment Analysis
For the Twitter sentiment analysis, I used a dataset of 43,158 tweets using the hashtag #galaxysedge from 10/17/19 to 7/15/20. Below are 2 visualizations of the top words in the dataset after text processing with the Natural Language Toolkit.

![Word Count](images/word_count.png)
![Word Cloud](images/word_cloud.png)


### Determining Sentiment
I used the Natural Language Toolkit to determine polarity (positive, neutral, or negative sentiment). Based on the polarity histogram below, you can see that sentiment is mostly neurtral and positive.

![Polarity Histogram](images/polarity_histogram.png)
![Sentiment Analysis](images/sentiment_analysis.png)

### Words Used With Positive Sentiment
![Positive Cloud](images/positive_cloud.png)

### Words Used With Neutral Sentiment
![Neutral Cloud](images/neutral_cloud.png)

### Words Used With Negative Sentiment
![Negative Cloud](images/negative_cloud.png)



## Clustering
![Elbow](images/elbow.png)
![Scatter](images/scatter.png)
![Cluster 1](images/cluster1.png)
![Cluster 2](images/cluster2.png)
![Cluster 3](images/cluster3.png)
![Top Features](images/top_features.png)

## Search Trends
![Monthly Searches](images/monthly_searches.png)
![State Searches](images/state_searches.png)
![Trend Map](images/trend_map.png)
