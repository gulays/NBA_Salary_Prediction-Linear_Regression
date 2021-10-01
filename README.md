# NBA Salary Prediction

In this project, I will explore the NBA player's performance statistics to predict a player's annual salary based on his game statistics throughout the season. The purpose is to 
provide fair salary expectations during recruiting process to the each side -  to players and teams.

## Data 
The data will be scraped from the [Basketball Reference](https://www.basketball-reference.com/) website. The metrics that will be collected are: 
- Players average game statistics in a season
- Players average annual salaries.

There are total 30 NBA teams and more than 400 players play in each season. To reach the desired amount of data asked for this project, I will collect statistics for 3 seasons. 
There will be some same players over 3 seasons.

Some tools that will be used are:
- BeatifulSoup to scrap the data.
- Pandas to organize/clean the data and for EDA.
- matplotlib for EDA.
- sklearn to build a linear regression

##  MVP Goal:
The EDA and the initial linear regression model. 

Back-up plan1: to predict [Box Plus/Minus metric](https://www.basketball-reference.com/about/bpm2.html) by using the data of players' game stats. 
Back-up plan2: to predict movie revenues using the data from Box Office Mojo.
