# Anime-Recommendations-Project

## Introduction
I was an avid anime fan and this lead me to pursue this project of creating a recommendation system for animes a user may enjoy based on their enjoyment of similar animes and similar people. This made me try to create both a content based filtering system and a collaborative filtering system to recommend animes to the user. What I would like to do is try combine both systems into one more effective system which eventually could be deployed as a website. 

## What I learnt:
- How to replace missing or sub-optimal values in a dataset
- Creating pairplot using seaborn to compare numerical data and distributions
- Use pandas and collections' counter to analyse frequency of values of multiple elements in strings.

## Included Files:
- Data Cleaning.ipynb (Notebook for cleaning the anime and ratings datasets that will be used)
- Exploratory Data Analysis.ipynb (Exploring the data and trying to extract insights and patterns before building the recommendation system)

## Resources and Datasets Used

**Python Version:** 3.8

**Packages:** pandas, numpy, matplotlib, seaborn

There is a `requirements.yml` file in the repo that contains all the packages I have used in this project. If you would like to install the packages easily, using Anaconda, run 
```
conda env create --name <<env name>> --file requirements.yml
```
#### Anime and Rating Datasets
Data was downloaded from https://www.kaggle.com/CooperUnion/anime-recommendations-database.
If you want to download the data from this repository and not the original source, you will need to either manually download them from Github, or install [Git LFS](https://git-lfs.github.com/) to download the data.
