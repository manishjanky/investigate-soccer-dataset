# investigate-soccer-dataset
Investigate the European Soccer Database

This was done as a project, part of the Data Analyst Nanodegree by Udacity.

#### Problem Statement
Choose one of Udacity's curated datasets and investigate it using NumPy and pandas. Go through the entire data analysis process, starting by posing a question and finishing by sharing your findings.

The [European Soccer Database](https://www.kaggle.com/hugomathien/soccer?) was selected to carry out this analysis.

#### Questions Posed and answered in the analysis
* Which team has scored maximum number of goals in all the matches played and how many?
* Which team has scored minimum number of goals in all the matches played and how many?
* In a match which team is more likely to win the match (home or away).
* What is the likelihood of a match with a result and not resulting in a tie?
* In what condition is a team more likely to score a goal?
* Which league has most number of goals scored?
* Which season has the maximum number of matches without a result?

#### Data cleaning/wrangling approach
This was concise decision take to avoid data cleaning as much as possible and only work with data that does not need extensive cleaning and in doing so SQL Inner joins were used and only those Columns were selectd which did not have the need for data cleaning. Still not relying solely on the fetched data checks were perfoemd after every database query for Null values and Duplicate records and if found were take care of accordingly. Steps performed for data wrangling:

* SQL JOINS (INNER) used to fetch data from the tables
* Checks for null values were performed
* Null valules if any vere dropped
* Checks for duplicate values were performed
* Duplicate records if any were dropped

#### Report
Check out the Report.html file for all the Visualizations and the Conclusion section for the anwers to the questions posed.

#### Code
Project 2 Investigate Soccer Dataset.ipynb Jupyter notebook contains all the code used in carryin out the analysis.

#### Dataset
The dataset *soccer.sqlite* was used which can also be downloaded from [Kaggle](https://www.kaggle.com/hugomathien/soccer?)

#### References
* https://www.kaggle.com/hugomathien/soccer? for better understanding of the dataset
* https://pandas.pydata.org/pandas-docs/stable/reference/frame.html for pandas documentation
* https://stackoverflow.com/ in other cases when needed help

#### Improvements/Suggestion
If you find and issues or have any suggestion that can help improve the analysis to help answer the posed question you are very welcome to do so by raising an issue here on Github.
