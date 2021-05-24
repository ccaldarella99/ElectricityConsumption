# Project 4
# *Hackathon*


## Contents
 - [Problem Statement](#Problem-Statement)
 - [Executive Summary](#Executive-Summary)
 - [File Directory](#File-Directory)
 - [Data](#Data)
 - [Data Dictionary](#Data-Dictionary)
 - [Conclusions and Recommendations](#Conclusions-and-Recommendations)
 - [Areas for Further Research/Study](#Areas-for-Further-Research/Study)
 - [Sources](#Sources)
 - [Visualizations](#Visualizations)


## Problem Statement
[back to top](#Project-4)

Using data from EIA (US Energy Information Administration) are there any patterns in electricity usage in the US before or during 2012.


## Executive Summary
[back to top](#Project-4)






## File Directory
[back to top](#Project-4)
### *Files should be clearly labeled with descriptive names*
03-Project<br />
|<br />
|__ code<br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ 00_table_of_contents.ipynb <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ 01_eda_and_cleaning.ipynb <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ 03_basic_models.ipynb <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ 04_models_with_gridsearch.ipynb <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ 05_models_without_body.ipynb <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ 06_conclusion.ipynb <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ functions.ipynb <br />
|<br />
|__ data <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ elec_mo_2001_2011_consumption.csv <br />
|<br />
|__ images <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ nothing.png <br />
|<br />
|__ presentation <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ ChrisCaldarella_project4_presentation.pdf <br />
|&nbsp;&nbsp;&nbsp;&nbsp;|__ ChrisCaldarella_project4_presentation.pptx <br />
|<br />
|__ LICENSE <br />
|__ README.md <br />


## Data
[back to top](#Project-4)

I found some data about Electricity usage on [Data Is Plural — Structured Archive document](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0), which led me to the [US Energy Information Administration webpage](https://www.eia.gov/electricity/data/state/) where I found a monthly data set of energy consumption by month over several years.


## Data Dictionary
[back to top](#Project-4)

| Feature              | Python Type | Data Type  | Descritpion   |
| ---                  | ---         | ---        | :---           |
| date                 | DateTime    | Continuous | Date; First of the Month |
| STATE                | Object      | Nominal    | State being observed |
| CONSUMPTION          | float64     | Continuous | Amount of total energy consumed that month |



## Conclusions and Recommendations
[back to top](#Project-4)




## Areas for Further Research/Study
[back to top](#Project-4)




## Sources
[back to top](#Project-4)

https://www.eia.gov/electricity/data/state/ <br/>



## Visualizations
[back to top](#Project-4)

### Null Model
