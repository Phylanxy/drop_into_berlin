# Drop into Berlin
## Problem
The user knows a certain place in Berlin that they liked and now they want to find something similar. 
Optional: The user describes a place in a text and our recommender extracts the features of this place and recommends something similar.

## Participants
- Leo Krohne
- Lukas Bauerschmidt

## Type of project
- Web scraping (Google API, Selenium)
- Feature extraction with NLP 
- Machine learning (clustering)

## Dataset
- Source: Scraped via Google Maps API and Tripadvisor API
- Shape: tbd (ca. 11k x 40 columns)
- Extract of Features:
- Name of location
- Location (Lattitude / Longitude)
- Type of Location
- Size of Location
- Expensiveness
- Nr. of reviews
- Adjectives
- Reviews
- Instances: 1 Instance = 1 Location

## Project breakdown
1. Building Restaurant Dataset for Berlin including above mentioned, not limited to, features
    - Scraping List of all restaurants of berlin including their reviews
    - Complementing dataset by tripadvisor and google maps data
2. Building own features based on scraped reviews of google maps and tripadvisor with the help of BERT or ChatGPT algorithm
3. Cluster restaurants with e.g. kmeans (á la Spotify Project)
4. Final Product: Recommender System that shows restaurant, that is most similar to the one inserted
1-4. Once ready with restaurant category, enhancing our recommender system with bars, clubs, monuments etc.

## User experience
1. User inserts
    - Place (restaurant, bar, club, museum, etc.) he/she finds interesting
    - Short textual description of the place
2. User get recommended
    - Place that shows highest match with inserted data

## Project plan

## 
