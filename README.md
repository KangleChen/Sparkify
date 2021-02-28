# Capstone Project: Spark Project
Project of  Udacity Data Scientist Nanodegree Program

### Table of Contents
- [Capstone Project: Spark Project](#capstone-project-spark-project) 
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Project Motivation](#project-motivation)
  - [File Descriptions](#file-descriptions)
  - [Results and Discussion](#results-and-discussion)
  - [Licensing, Authors, Acknowledgements](#licensing-authors-acknowledgements)

## Installation

Required packeages are listed in `requirement.txt`. 

## Project Motivation

In this project, the process of a comprehensive implementation of data science knowledge in realworld project is demonstrated, which includes following steps: 

1. Define project, analysis and modeling following the CRISP-DM process 
2. Using Spark Dataframes and Spark ML to manipulate data and build machine learning model

## File Descriptions

1. File `Sparkify_python` and `Sparkify_spark` contains the scripts using pandas and spark. 
2. Directory `data` contains the origin data `mini_sparkify_event_data.json` and the dataframe with generated features `data_ubc.json` 

## Results and Discussion

Through data processing and feature generating, an accurate machine leanring model has been trained. The model has demonstrated that most users churned the payment after using the service for 1500 hours ~ 2500 hours. Coupon and discounts for users in this period might be effective, which certainly still requires validation from for example A/B test. 

Due to the restriction of computation power, `GridSearchCV` here is only to demonstrate the pipeline to employ it rather than to provide optimized trained results. 

Finally, since the dataset is not large, Spark has actually not shown its advantage over python and pandas. A further task is to employ the model in aws with larger data. 

## Licensing, Authors, Acknowledgements

Must give credit to Udacity for the project. Otherwise, feel free to use the code here as you would like!



