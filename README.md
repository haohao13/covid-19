# COVID-19 Challenge
### Team: Indoorsy Aggies

### Core Workbooks
1. covid-19.twb \
Includes all graphs related to spreading center. 

2. COVID-19 Data Manipulation.ipynb \
Aggregated movement data and covid-19 related (positive, negative, tests, etc.) data for each state in the US.

Data source:\
https://github.com/COVIDExposureIndices/COVIDExposureIndices/tree/master/lex_data \
https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset \
https://covidtracking.com/api/us/daily.csv \
https://worldpopulationreview.com/states/state-abbreviations/ \
\
Output datasets: \
transition.csv (movement among states in US) \
covid_data.csv (includes state population) \
daily_data.csv (includes tests)

3. Italy_and_USStates.Rmd \
Aggregated data into one dataset that combines daily confirmed and test data of Italy and states in the US.

4. NY_transition_cases.ipynb \
Merge transition data that only includes NY travel history and the data that document the number of positive cases of each state.
