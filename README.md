# Predicting-Board-Game-Reviews

Predicting board game reviews

Introduction

In this project, we'll be working with a data set that contains 80000 board games and their associated review scores. The data was scraped from BoardGameGeek and compiled into CSV format by [Sean Beck](https://github.com/ThaWeatherman). The data set is stored in board_games.csv.

Each row represents a single board game, and has descriptive statistics about the board game, as well as review information. Here are some of the interesting columns:

- name: name of the board game.
- playingtime: the playing time (given by the manufacturer).
- minplaytime: the minimum playing time (given by the manufacturer).
- maxplaytime: the maximum playing time (given by the manufacturer).
- minage: the minimum recommended age to play.
- users_rated: the number of users who rated the game.
- average_rating: the average rating given to the game by users. (0-10)
- total_weights: Number of weights given by users. Read more about what BoardGameGeek considers weights [here](http://boardgamegeek.com/wiki/page/Weight).
- average_weight: the average of all the subjective weights (0-5).
