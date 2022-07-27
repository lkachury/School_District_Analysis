# School_District_Analysis

Here is the list of deliverables for the analysis of the school district: 

A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school
Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.

The school district summary will be a high-level snapshot of the district's key metrics:

Total number of students
Total number of schools
Total budget
Average math score
Average reading score
Percentage of students who passed math
Percentage of students who passed reading
Overall passing percentage
We'll find this information and visualize the data with a table like the following:




Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, 

reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. 

She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 

Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

This new assignment consists of two technical analysis deliverables and a written report to present your results. You will submit the following:
Deliverable 1: Replace ninth-grade reading and math scores
Deliverable 2: Repeat the school district analysis
Deliverable 3: A written report for the school district analysis (README.md)

Deliverable 1 Instructions
Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.




## Overview 

Given access to every student’s math and reading scores and school information, assist a city school district chief data scientist to analyze data on student funding and standardized test scores. In order to assist the school board and superintendent in making decisions regarding the school budgets and priorities, we need to aggregate the date and showcase trends in school performance. Utilize the Jupyter Notebook package from Anaconda and the Pandas python library to read the raw data, clean and inspect the data, merge the datasets, perform calculations and create tables. The initial analysis of the school district presents a high-level snapshot of the district's key metrics and an overview of the key metrics for each school consisting of the 5 top and bottom performing schools, average math and reading scores received by students in each grade level at each school, and school performance based on budget per student, school size, and school type. 

## Purpose

The school board cautioned that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Since the full extent of the academic dishonesty is unknown, the Thomas High School ninth grade math and reading scores will be replaced with NaNs while keeping the rest of the data intact. The purpose of this challenge is to repeat the school district analysis with the replaced math and reading scores and describe how these changes affected the initial school district metrics.


## Results

Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?
How is the school summary affected?
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


