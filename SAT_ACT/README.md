# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Problem Statement

College Board the maker of the SAT would like to increase participation in a state. They would like to know the state that has the best chance for an impact.

---

### Datasets

#### Provided Data

From project READ.md
For this project, you'll have two provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.

You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Additional Data

2018 state-by-state average results and participation for the SAT are available in PDF reports [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 2018 ACT state-by-state mean composite scores and participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .


---

### Data Dictionary 

|Feature|Type|Dataset|Description|
|---|---|---|---|
state|object|ACT/SAT|US State and DC
act_2017_participation|int64|2017 ACT|Precentage of high school students taking the ACT in 2017 by state
act_2017_english|float64|2017 ACT|Average ACT english score by state
act_2017_math|float64|2017 ACT|Average ACT math score by state
act_2017_reading|float64|2017 ACT|Average ACT reading score by state
act_2017_science|float64|2017 ACT|Average ACT science score by state
act_2017_composite|float64|2017 ACT|Average ACT composite score by state
sat_2017_participation|int64|2017 SAT|Precentage of high school students taking the SAT in 2017 by state
sat_2017_evidence-based reading_and_writing|int64|2017 SAT|Average SAT state evidence-based reading and writing score by state
sat_2017_math|int64|2017 SAT|Average SAT math score by state
sat_2017_total|int64|2017 SAT|Average SAT total score by state
act_2018_participation|int64|2018 ACT|Precentage of high school students taking the ACT in 2018 by state
act_2018_composite|float64|2018 ACT|Average ACT composite score by state
sat_2018_participation|int64|2018 SAT|Precentage of high school students taking the SAT in 2018 by state
sat_2018_evidence-based reading_and_writing|int64|2018 SAT|Average SAT state evidence-based reading and writing score by state
sat_2018_math|int64|2018 SAT|Average SAT math score by state
sat_2018_total|int64|2018 SAT|Average SAT total score by state




---


### Conclusions:

SAT and ACT participation are inversely correlated. By looking at states that have low SAT participation rates and have a high population, I was able to narrow a range of target states. Also by looking at the legal requirements	of those states. Arizona is the best choice to pursue spending money to increase participation. They have already have an option to replace standardized testing with the SAT or ACT, their current program is not inline with federal law and the could lose up to 340 million dollars if they do not comply. This is a good time to try to convince the state that they should replace standardized testing for juniors with the SAT.