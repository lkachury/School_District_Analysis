# School_District_Analysis

## Overview 

Given access to every student’s math and reading scores and school information, assist a city school district chief data scientist to analyze data on student funding and standardized test scores. In order to assist the school board and superintendent in making decisions regarding the school budgets and priorities, we need to aggregate the date and showcase trends in school performance. Utilize the Jupyter Notebook package from Anaconda and the Pandas python library to read, clean and inspect the data, merge  datasets, perform calculations, and create tables. The initial analysis of the school district presents a high-level snapshot of the district's key metrics (total number of students, total number of schools, total budget, average math and reading scores, percentage of students who passed math and reading, and overall passing percentage) and an overview of the key metrics for each school (5 top and bottom performing schools, average math and reading scores received by students in each grade level at each school, and school performance based on budget per student, school size, and school type). 

### Purpose

The school board cautioned that the students_complete.csv file showed evidence of academic dishonesty; specifically, the Thomas High School ninth grade reading and math scores appeared to have been altered. Since the full extent of the academic dishonesty is unknown, the Thomas High School ninth grade math and reading scores will be replaced with NaNs (by using the Pandas Numpy library) while keeping the rest of the data intact. The purpose of this challenge is to repeat the school district analysis with the replaced math and reading scores and describe how these changes affect the initial school district metrics.

## Resources
### Data Source 
- schools_complete.csv
- students_complete.csv

### Software
- Python 3.7.6
- Conda 4.13.0
- Jupyter Notebook 
- Dependencies:
  - Python Pandas Library
  - Python Numpy Library

## Results

The full Jupyter Notebook can be referenced here: https://github.com/lkachury/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb

1. How is the district summary affected?

Initial School District Summary DataFrame:
![ds2](https://user-images.githubusercontent.com/108038989/181267105-053a8563-69b4-415b-ab54-daa65f980796.png)

Replaced Scores School District Summary DataFrame:
![ds1](https://user-images.githubusercontent.com/108038989/181267117-86a70221-3c5e-44d0-a5bd-f8d78b939ccf.png)

2. How is the school summary affected?

Initial School Summary DataFrame:


Replaced Scores School Summary DataFrame:


3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


4. How does replacing the ninth-grade scores affect math and reading scores by grade?



5. How does replacing the ninth-grade scores affect math and reading scores by school spending?



6. How does replacing the ninth-grade scores affect math and reading scores by school size?



7. How does replacing the ninth-grade scores affect math and reading scores by school type?


## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


