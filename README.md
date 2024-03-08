# BrainStationCapstone
NHL Trade Deadline Strategies: Prioritizing All-Stars vs Role-Players

## Subject Area Overview
### Problem Statement/Opportunity
- Every year NHL teams compete for a place in the Stanley Cup Playoffs.
- I will employ machine learning to assess whether a team's playoff performance can be predicted based on their trade-deadline activity.
### NHL Background Info
- 32 Teams (30 teams from 2006 - 2016 ; 31 teams 2017 - 2020)
- 16 Teams qualify for playoffs
- 'Trade Deadline' - final date for in-season (intrateam) transactions
- "Buyers" - teams competing for playoffs
-   Trade future assets for proven players
-   Focus maybe on All-Stars, Role-Players, or a combination
- "Sellers" - teams not conentending in current season
-   Trade away current players, often on 'expiring contracts' for future assets
-   Players on "Expiring Contracts" may leave for another team after season concludes
-     Would result in no return for the "sellers"

## Vision
- Use Data Science and Machine Learning to classify player types (All-Star vs Role-Player) based on numerous individual statistics
- Use Machine Learning to build a model able to assess a team's relative success based on their transactions (among other factors), and ultimately how much this contributes to whether they won the Stanley Cup or not
- Use previous season data to predict how teams will fare in the current season, although the playoffs will not begin until after the end of this bootcamp

## Potential Impact
- In season trades can affect the "locker room" culture built over the previous months of the season. An "All-Star" will generally have a greater impact on this culture
- The Assets to acquire an "All-Star" are often significant, and likely will have ramifications in succeeding seasons
-   While these are difficult impacts to quantify, offering statistical evidence, could lead to suggesting different strategies for teams to employ in the future

## Data Overview
- Hockey Trades Since 1918 (Kaggle) - incomplete dataset, but used for preliminary EDA
- CapFriendly - Web Scraping to complete transaction data, can also use for salary cap information
- Hockey Reference - Vast amounts of NHL Player and Team Data available via csv files
-   Use to classify player significance, quantify team success

## Current Issues / Next Steps
- The API I was planning to use for the majority of my data is meant for enterprise use, and is too expensive to reasonable use for a student project.  So a bit behind on data retrieval.
- Web Scraping from Cap Friendly is primary next step -> Implement web driver to drill into the correct data from 2006 - present
-   Once full data set is put together, further EDA can be employed
