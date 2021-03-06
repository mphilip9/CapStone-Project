---
Proposal for Capstone Project
--- 

**Problem**: The NBA is a sports league on the rise. It has a growing fanbase overseas (a professional league is currently being established in Africa with the help of the NBA), and since it lacks the stigma of CTE, it appears poised to steal some of the market share away from the NFL. There are a number of awards given out at the end of each season for various accomplishments, including the most improved player award (MIP). This award is given to the player who has shown the most progress during the regular season. Typically this means players that greatly increased their counting stats compared to their previous seasons in addition to overall player development. The proposal is to use data from the introduction of this award (1986) to the end of the last season (2018) to develop a machine learning algorithm that accurately predicts a player's probabilty of winning the award.

**Who would care about this?**: Sportwriters are the ones who vote for the award, and so are likely to be interested in seeing who the likely winners are, statistically speaking. Since there are so many different counting stats and a number of advanced statistics regarding playerse in the league, there are a number of fans who obsess over the numbers surrounding the game. Meaning sports analysts would be wise to base their speculation on statistics. Besides the media, sports betting agencies will want to be able to track a player's probability for winning the award in order to place the proper odds on the bet.

**Data Sources**: The data will be pulled from a data-set on Kaggle, which in turned was scraped from *Basketball-reference* (https://www.kaggle.com/drgilermo/nba-players-stats/version/2). This data set contains player statistics from the past 67 seasons with 53 attributes, as well as some player information like the college team they played for and their home town. A listing of the winners of the MIP award will also be referenced (http://www.espn.com/nba/history/awards/_/id/36).

**Problem Solution**: In order to predict the award winner, building a classification algorithm is likely the best approach. This algorithm will classify each input as either a MIP award winner or Not a MIP award winner, and it will give the probability for both classes. At this time, it is unknown which classificaiton model will work best, so it is likely a number of them will be employed to determine a best fit. Only player data from the introduction of the award onwards will be used. Attributes/statistics that may hinder the model's accuracy due to differences in an era's playstyle should be noted and possibly removed. 

**Deliverables**: 
  *Code
    +Data wrangling cleaning
    +Exploratory Analysis
    +Implementation of Machine Learning 
  
  *Final Capstone Project Report
  *Slide Deck for Project Presentation
