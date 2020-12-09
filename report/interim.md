# TITLE:
## Team Members:Jacob Caldwell & Millon Mclendon
## Date: 11/12/2020

# Project Description
## Probelm Statement and Motivation
We aim to analyze MLB data to better come up with a plan to form a winning forumla and improve a teams overall odds of winning. This motivation comes from our love for sports and simply wanting to improve our "teams" chances of winning.

## Introduction and Description of Data
This problem is important because there has been a recent shift within professional baseball to use numerical analysis of statistics to adapt there team and to optimize their playstyle in order to perform better. Teams are using these numbers to try to win more games and as a result make their teams more successful.

This problem is challenging because there are multiple statistics that are used in collaboration with others that help teams to determine a player's worth. We are attempting to use some of these statistics to help better gauge a player's worth to the team, which is a challenging and complex problem that many teams are still trying to solve

## Literature Review/Related Work
The literature we collected during our project mainly reflected different approaches researchers used to make inferences on games, but also trying to gain knowledge of the angles used and possibly new angles to come from.

[1] Valero, C. S. (2016). Predicting Win-Loss outcomes in MLB regular season games–A comparative study using data mining methods. International Journal of Computer Science in Sport, 15(2), 91-112.

[2] Sommers, P. M. (2008). The changing hitting performance profile in major league baseball, 1966-2006. Journal of Sports Economics, 9(4), 435-440.

[3] “Scikit-Learn Tutorial: Baseball Analytics in Python Pt 1.” DataCamp Community, www.datacamp.com/community/tutorials/scikit-learn-tutorial-baseball-1. 

## Interim Results
To start with, we began to determine the specific stat that we wanted to find and compare between different players. We decided to look into how well each player bats and compare each player's batting average as a way to show their individually value. The batting average was not something that was given in the data frame, so we had to calculate this value ourselves. To do this, we took the values of "Hits" and divided them by their accompanying values "At Bats". We were then able to get a better comparison between each players and were able to narrow our results. We also decided to eliminate outliers by dropping any rows that did not have a set minimum number of At Bats, as a way to make sure people that batted only a handful of times did not have a very large or small Batting Average.  

# Project Progress
This could include the __revised__ major timeline and milestones of your project as well as requirements of computing and storage resources. 

This may also include a brief summary of your team's progress on the project and a candid reflection of what's gone wrong and what's gone right, and what efforts that your team have taken or are going to takea to overcome any issue that comes out during the course of the project.

# References:
https://data.world/makeovermonday/2019w19/workspace/file?filename=MLB%20Stats.csv We will be using data.world for most of our csv files on MLB statistics and also adding more research papers in the future.
