# Identifying Which Runningbacks That Might Score More or Less Touchdowns in 2023
## Table of Contents

- [Overview](#overview)
- [Skills & Tools](#skills-&-tools)
- [The Rankings](#the-rankings)
- [Contact Me](#contact-me)
- [Acknowledgements](#Acknowledgements)

## Overview
If you have ever played fantasy football before, you will immediately recognize how important touchdowns are. Touchdowns lead to huge swings in fantasy football matchups and it would be a fantastic if we had some pointers to whether players might score more or less touchdowns in the future. Luckily, that's what this study focuses on. Using touchdown regression analysis, this study analyzes which runningbacks overperformed or underperformed their expected touchdown total in 2022. This will allow owners to understand which runningbacks to draft based on prior touchdown performances versus their expected touchdowns.

I was able to design this touchdown regression model using play by play data from the 2018 NFL season through the 2022 NFL season. By combining running play probabilities and scoring regression analysis, I am able to present to you runningbacks to target and avoid based on their likelihood of scoring more or less touchdowns in 2023. Enjoy!

## Skills & Tools
- Python
    - Libraries: Numpy, Pandas & Seaborn
- Regression model
- Probability aggregation	

## The Rankings
The project and process of how the touchdown regression candidates were developed can be found here: [The Project](https://github.com/NihalSidhu/Runningback-Touchdown-Regression/blob/main/Runningback_TD_Regression_Candidates.ipynb).

The final touchdown regression candidate rankings can be found here: [The Candidates](https://github.com/NihalSidhu/Runningback-Touchdown-Regression/blob/main/RunningbackTouchdownRegressionRankings.csv).

## Contact Me
Email: [nihalsidhu1@gmail.com](mailto:nihalsidhu1@gmail.com])

LinkedIn: [Nihal Sidhu](https://www.linkedin.com/in/nihal-sidhu/)

## Acknowledgements
A big thank you to NFLFastR for having setup modules that allow for easy reading of play by play data. 
Using NFLFastR, I was able to pull the play by play data from 2018 through 2022 using the nfl_data_py library from NFLFastR. You can view more information about NFLFastR [here](https://www.nflfastr.com/).
