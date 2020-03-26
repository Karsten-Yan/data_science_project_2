# Kickstarter Success or Fail Prediction

Collaborative work from [Marc M.](https://github.com/mmwieauchimmer) and [Karsten Y.](https://github.com/Karsten-Yan).

Raw Data is found in the [Data Folder](https://github.com/Karsten-Yan/data_science_project_2/tree/master/data).

[Project 2 EDA.ipynb](https://github.com/Karsten-Yan/data_science_project_2/blob/master/Project%202%20EDA.ipynb) contains the EDA and statistical Analysis of the project, focused solely on factors that are known before the start of a kickstarter campaign.

The Notebook is split into 9 Categories:

1. Data Mining:
* Accession of all csvs

2. Data Cleaning:
* removal of unnecessary columns and removal of NaNs

3. Feature Engineering
* Location
* average pledge
* convert goal to usd
* formulation of categories
* name length
* launch month
* launch year
* launch day
* deadline day
* duration
* description length

4. Data Exploration
* removal of live and cancelled
* countries
* goal
* boolean features
* name length
* year and date

5. Modelling Preparation
* drop of all columns unnecessary for modelling 
* outlier removal
* correlation matrix and pair plots
* train test split
* profile ids after train test split

6. modelling
* model selection
* hyperparam tuning
* validation test

7. Visualizations

8. Example Case

9. Future Work
