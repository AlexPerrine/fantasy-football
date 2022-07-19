# fantasy-football
Getting historical NFL data to try and win my fantasy football league.

# Project Outline
1. Collect data from 2018-2021 for the NFL players
   - Clean the data
   - Feature engineering
   - Use data in Tableau to create charts to analyze the data
2. Collect drive level data from 2021 for each NFL game
   - follow along with https://www.youtube.com/watch?v=eYQyKwivgFs&t=159s to transform the data
   - Join this data with the 2021 player stats
   - Create visualizations with the joined data to
3. ML regression model to predict what each player will do each week.
   - Use each player's historcal averages to help draft team
   - Once season has started update trained data with the current year's production
   - Use this to set weekly lineups


Things I want to do:
Store the data collected in the cloud (AWS or GCP)
Hook dbt up to the data for model creation
Connect to an API for data pulling
Maybe use python visualization tools?


# Finished Product
This is what I see will be the finished product as of 7/19/2022
- A tool that will let you see a player's historical stats and production
- A tool that will generate drive level stats for each team
- A tool that will let you compare your team's weekly projected points based off of who that player is playing against by comparing their production v. the opposing team's offensive/defensive statistics generated from following along the youtube video above.

<strong>Note</strong> : This could be 2 separate tools: one for fantasy football one for betting on games