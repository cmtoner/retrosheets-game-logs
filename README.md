# retrosheets-game-logs
*The information used here was obtained free of charge from and is copyrighted by Retrosheet. Interested parties may contact Retrosheet at "www.retrosheet.org".*

Major League Baseball game logs are summaries of games from 1871-present containing admininstrative information (time/date, location, participants, etc.) as well as team counting statistics such as winning/losing scores, number of hits, walks, and strikeouts. We analyze the counting statistics in the game logs in four parts:

1. Exploratory Data Analysis, Part 1. Examine the counts of the on-field events over time and with respect to rule changes. The goal is to identify a period of time where the offensive environment is relatively stable and suitable for developing a regression model for the number of runs scored per game. 

2. Exploratory Data Analysis, Part 2. Examine how the various statistics are distributed. The goal is to identify a suitable parametric distribution(s) to model the counts of on-field events for use in a regression model or discrete event simulation.

3. OLS Regression Model. Develop and evaluate an ordinary least squares (OLS) regression model for the number of runs per game scored by a team. The goal is inferenece: we want to quantify the effect of each counting statistic on offensive production. 

4. GLM Regression. Improve the OLS model with a generalized linear model (GLM). Any departures from the assumptions of an OLS model can result in unreliable parameter estimates and confidence intervals. The goal is to address those problems using with a GLM and evalute its performance.
