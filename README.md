# Anime-Recommendations-Project

## Introduction
I was an avid anime fan and this lead me to pursue this project of creating a recommendation system for animes a user may enjoy based on their enjoyment of similar animes and similar people. This made me try to create both a content based filtering system and a collaborative filtering system to recommend animes to the user. What I would like to do is try combine both systems into one more effective system which eventually could be deployed as a website. 

## What I learnt:
- How to replace missing or sub-optimal values in a dataset
- Creating pairplot using seaborn to compare numerical data and distributions
- Use pandas and collections' counter to analyse frequency of values of multiple elements in strings.
- Create content based recommendation system using the genres of a show and a user's ratings of watched shows

## Included Files:
- Data Cleaning.ipynb (Notebook for cleaning the anime and ratings datasets that will be used)
- Exploratory Data Analysis.ipynb (Exploring the data and trying to extract insights and patterns before building the recommendation system)
- Content Based Filtering.ipynb (Notebook containing the code for the content based recommender)
- Collaborative Filtering.ipynb (Notebook containing the code for the collaborative filtering recommender)
- anime.csv (Original anime dataset)
- rating.csv (Original user and rating data)
- cleaned_anime.csv (The cleaned and processed anime dataset after data cleaning)
- cleaned_rating.csv (The cleaned and processed rating dataset after data cleaning)

## Resources and Datasets Used

**Python Version:** 3.8

**Packages:** 
- pandas 1.13
- numpy 1.19.2
- matplotlib 3.3.2
- seaborn 0.11.0
- scikit surprise 1.1.1

#### Anime and Rating Datasets
Data was downloaded from https://www.kaggle.com/CooperUnion/anime-recommendations-database.
If you want to download the data from this repository and not the original source, you will need to either manually download them from Github, or install [Git LFS](https://git-lfs.github.com/) to download the data.
