This repository contains data used in the study entitled "Estimating Positional Plus-Minus in the NBA".

data/stint contains NBA stint data from 2015-16 to 2021-22. 2019-20 season data are not included. Stint data are extracted from NBA play-by-play data sets.

data/stint_garbage contains the same stint data as the data from data/stint, except they are extracted from NBA play-by-play data sets with garbage time removed.

data/playerId/nba_id_data contains NBA player ID and official position data collected from the NBA official statistics website.

data/playerId/nba_playType_data contains NBA play type data from 2015-16 to 2021-22. 2019-20 season data are not included. Play type data track the total number of offensive possessions played under different actions.Play type data are collected by Synergy Sports and are published on the NBA official statistics website.

NBA website notes that only players with at least 10 minutes per game playing time will have play type data. In addition, at least 10 possessions per play type are needed to have that play type data. Therefore, the NAs in the data set mean the player played fewer than 10 possessions under that play type
