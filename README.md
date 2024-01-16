# NFL Big Data Bowl 2024

This repository is my code and analysis for the [NFL's 2024 Big Data Bowl](https://www.kaggle.com/competitions/nfl-big-data-bowl-2024/overview) on Tackling. My submission can be found [here](https://www.kaggle.com/code/ricdur/defensive-tackling-contribution-dtc/). Overall, my objective is to create a metric called Defensive Tackling Contribution (DTC) that attempts to assign credit to the defenders who contributed to a tackle on the play.

My code and naming are more inefficient and confusing than I'd like. Part of this is due to brainstorming different ideas as I went along, but overall I'm looking to be better at sharing what I've done publicly. The notebooks can be followed in the following order:

  1) DataCleaning_1: Takes the initial player tracking data and creates week 1-9 dataframes with further data to be used in 'DataCleaning_2'
  2) DataCleaning_2: Further cleans and organizes the data to be ready for modeling
  3) XGBoost_and_SHAP: Creation of the model and SHAP values
  4) Tackling_Data: More data cleaning and organizing to create Defensive Tackling Contribution (DTC) metric
  5) Data_Viz_and_Insights: Data visualizations as found in the submission
