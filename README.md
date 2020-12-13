# Recommendations with IBM



## Table of Contents
1. [Introduction](#introduction)
2. [Objetives](#objetives)
3. [Getting Started](#getting_started)
4. [File Structure](#files)
5. [Authors](#authors)
6. [License](#license)
7. [Acknowledgement](#acknowledgement)

<a name="descripton"></a>
## Introduction

For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.
Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, you will be performing a study of the data available on the IBM Watson Studio platform. 
<a name="objectives"></a>
## Objectives

The project will be divided into the following tasks

I. Exploratory Data Analysis
II. Rank Based Recommendations
III. User-User Based Collaborative Filtering
IV. Matrix Factorization

<a name="description"></a>
## Description

When looking at the data, these are the categories that have selected for the 
data set.
The Figure Eight is used for many of the disasters from which messages were 
pulled, then combined the data sets and re-labeled them
to have consistent labels across different disasters. 
This is to allow to investigate the different trends that can found
and build supervised machine learning models to help respond to future disasters.
The aim of the project is to build a Natural Language Processing (NLP) tool that categorize disaster messages.

The Project is divided in the following Sections:

1. Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper database structure.
2. Machine Learning Pipeline to train and tunning a model able to classify text messages into appropriate categories.
3. Web App to show model results in real time. 

<a name="getting_started"></a>
## Getting Started

The project contains all files needed. It's necessary just run the jupyter notebook
cells or read the .html file to understand the steps.

<a name="clone"></a>
## Clone repository

Clone this GIT repository:

```
git clone https://github.com/ordepzero/recommendations_with_ibm
```

<a name="file"></a>
## File Structure

* `data` folder contains the following:
  * `articles_community.csv`: information file  articles
  * `user-item-interactions.csv`: information file with user interactions with item 
* `project_tests.py` python file with functions to verify the results
* `README.md` this article
* `Recommendations_with_IBM.html` jupyter notebook project converted into html
* `Recommendations_with_IBM.ipynb` jupyter notebook project
* `top_5.p` Stores some results
* `top_10.p` Stores some results
* `top_20.p` Stores some results

<a name="authors"></a>
## Authors

* [ordepzero](https://github.com/ordepzero)

<a name="license"></a>

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

<a name="acknowledgement"></a>

## Acknowledgements

* [Udacity](https://www.udacity.com/) for providing such a complete Data Science Nanodegree Program
