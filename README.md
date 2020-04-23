# COVID-19 Challenge
### Team: Indoorsy Aggies

### Project Summary Presentation
The Spreading Center of U.S. - Indoorsy Aggies.pptx

### Core Workbooks
1.covid-19.twb \
Identify spreading center. 

2.map and motion.twb \
Confirmed cases in states of US over time on a map.

3.NY Italy Comparison.twb \
Comparison between COVID 19 spreading trends in NewYork and Italy.

4.COVID-19 Data Manipulation.ipynb \
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

5.Italy_and_USStates.Rmd \
Aggregated data into one dataset that combines daily confirmed and test data of Italy and states in the US.

Input files: \
combined_confirmed.csv (contains data of confirmed cases of several countries over time) \
full_list.csv (contains data of tested cases of several countries over time)

Output file: \
Italy_US.csv

6.NY_transition_cases.ipynb \
Merge transition data that only includes NY travel history and the data that document the number of positive cases of each state.

