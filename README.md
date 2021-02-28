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

File `Sparkify` contains the pyspark scripts. 
The dataset is not loaded because it is too big. You can easily find it by google 'mini_sparkify_event_data.json'. 

## Results and Discussion

Through data processing and feature generating, an accurate machine leanring model has been trained. The model has demonstrated that most users churned the payment after using the service for 1000 hours ~ 2000 hours. Coupon and discounts for users in this period might be effective, which certainly still requires validation from for example A/B test. 

Due to the restriction of computation power, `CrossValidator` and `paramGrid` here are only to demonstrate the pipeline to employ it rather than to provide optimized trained results. 

Finally, since the dataset is not large, Spark has actually not shown its advantage over python and pandas. A further task is to employ the model in aws with larger data. 

## Licensing, Authors, Acknowledgements

Must give credit to Udacity for the project. Otherwise, feel free to use the code here as you would like!



