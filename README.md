## INTRODUCTION
Welcome to my BrainStation Capstone project on trying to predict NHL teams' playoff success based on their midseason transactions.  After three months working in this bootcamp and learning Data Science, I wanted to put the tools I've learned and skills I've developed to use on a project I am passionate about - hockey!  The inspiration here, is that as much as I love playing and watching hockey, I also have always been very intrigued with the player management side of things.  

To do this, I compiled data on NHL teams' preseason odds, midseason standings, and player transactions, as well as various player statistics and all-star records.  My goal here is to aggregate the data and use machine learning techniques in effort to predict whether all-star players or role players traded during the season would offer a greater boost to a team's chances of winning the Stanley Cup.  Given time constraints, the main focus here was to start with a narrower scope of team data and whether a player actually played in an all-star game rather than focusing on the "best" players in the league statistically.  I do hope to dive further into this study to see whether a player's statistics offer a better definition of an all-star than one who played in an all-star game.

## METHODOLOGY
#### DATA COLLECTION
-Player transaction data obtained by webscraping from CapFriendly
-NHL Player data on Active players and all-star appearances obtained from NHL Reference
-NHL Team data on preseason odds and playoff results obtained from NHL Reference
-NHL Team Midseason standings obtained from SHRP Sports
#### DATA EXPLORATION / PROCESSING
-Convert various data sets into format for analysis
-Clean data to focus on certain seasons, midseason time-frames, and statistics
-Combine dataframes from various sources
-Explore distributions and relationships within the data
#### MODELING
-Baseline model predicting a teams success without trade data using Logistic Regression
-Iterating through various other models including trade data including Logistic Regression, Ridge Classifier, Random Forest Classifier
-Pipeline / Gridsearch to explore optimal model and hyperparameters

## CONCLUSION / LEARNINGS / NEXT STEPS
-This was a fun project to test myself and what I've learned over the past few months.  While I didn't find any significance in whether trading for an all-star would offer a team any significant difference in their chances of winning the Stanley Cup, I definitely learned plenty, and look forward to further exploring this question. Some key takeaways include getting a real example of how much work often needs to be done with data in effort to try and prove a hypothesis.  I look forward to continue improving my coding skills while diving further into a second portion of the project in effort to define an 'all-star' and a 'role-player' on statistics rather than solely whether a player was voted into an all-star game.  Taking more factors into consideration should offer far more into a players value rather than whether they were the best or most popular player on their team.

#### CONTENTS
-Data contains csv files used in or derived from Python Notebooks
-Notebooks contains coding work and analysis, as well as work done modeling
-Presentation contains the final presentation for class
