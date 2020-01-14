# :movie_camera: Movie Gathering Project -  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/deepaksithu/Movie_Gathering_Project/master?filepath=gathering.ipynb)

Movie Gathering Project is a project submission for the Udacity Data Analyst Nanodegree. The project scrapes and cleans web data to create a data set of the top 100 ranked films on Rotten Tomatoes.

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements) 
- [Issues](#issues) 
- [Contact](#contact)

## Overview

This project uses a data set, `bestofrt.tsv`, which contains a list of the top 100 films on Rotten Tomatoes based on the websites own rankings, which are derived from the average critic's score. The data set has columns for ranking, critics score, title of the film, and the number of critics scores. From there the web pages for each film on Rotten Tomatoes are accessed and scraped using the `requests`, `os`, and `BeautifulSoup` libraries to find the audience ratings and the count of audience ratings for each film, which are then saved as their own data set.

## Requirements

This code depends on the following libraries:
1. `zipfile`
2. `pandas`
3. `requests`
4. `os`
5. `BeautifulSoup` from `bs4`

In addition to these, the Jupyter Notebook assumes that the data set, `bestofrt.tst` is in the project folder.

The Binder badge above can be used to explore an executable environment for this project.

## Issues

- save second data set as .csv
- review project for further applications

## Contact
You can get in touch with me on LinkedIn [![LinkedIn Link](https://img.shields.io/badge/Connect-deepaksithu-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect
)](https://www.linkedin.com/in/deepaksithu) <br>
give me that choice follow on Github      ![GitHub followers](https://img.shields.io/github/followers/deepaksithu?style=social)<br>
or email me at deepaksithu@gmail.com.
