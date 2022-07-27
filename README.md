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

### 1. How is the district summary affected?

Initial School District Summary DataFrame:
![ds1](https://user-images.githubusercontent.com/108038989/181275088-2d3509c6-4a54-4aca-a902-aad2197abbbb.png)

Replaced Scores School District Summary DataFrame:
![ds2](https://user-images.githubusercontent.com/108038989/181275547-ef4cea38-a8a2-413f-ba44-5ea0c2a2f78f.png)


### 2. How is the school summary affected?

Before School Summary DataFrame:
![image](https://user-images.githubusercontent.com/108038989/181284429-29deb17f-0f3d-4949-aba8-78bd423cab69.png)


Replaced Scores School Summary DataFrame:
![image](https://user-images.githubusercontent.com/108038989/181285422-8134d1d3-73c8-4596-b62c-f4d10ab3c3a5.png)




### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


Before:
Top 5:
![image](https://user-images.githubusercontent.com/108038989/181282914-b1b2dc3f-6318-4af4-8fd2-adc741db6d16.png)

Bottom 5: 
![image](https://user-images.githubusercontent.com/108038989/181283055-702f18d3-4c4c-44c0-825f-eec536c341ed.png)







After
Top 5 Performing Schools After Replacing Scores:
![image](https://user-images.githubusercontent.com/108038989/181278198-666aba1b-4154-46fd-8da4-17ef21cce2f7.png)


Bottom 5 Performing Schools After replacing Scores:
![image](https://user-images.githubusercontent.com/108038989/181278469-6c81bbdf-a59a-46c3-a3cd-7628cad42d32.png)





### 4. How does replacing the ninth-grade scores affect math and reading scores by grade?

Math Scores

![image](https://user-images.githubusercontent.com/108038989/181280667-9ec8d134-f383-402c-bdaf-797761a44339.png)


Reading Scores

![image](https://user-images.githubusercontent.com/108038989/181280433-8889b153-6b85-44c3-8559-343eed2885ec.png)




### 5. How does replacing the ninth-grade scores affect math and reading scores by school spending?

Before: 
![image](https://user-images.githubusercontent.com/108038989/181282546-4e00e66a-d77e-4501-9a02-2ab3cea726de.png)


After:
![image](https://user-images.githubusercontent.com/108038989/181281085-9c96937b-d6da-4569-974e-ddee49ed97c5.png)


### 6. How does replacing the ninth-grade scores affect math and reading scores by school size?

Before 
![image](https://user-images.githubusercontent.com/108038989/181282227-2b357ddf-b4f8-44f8-8a6a-98df2c4f5fd3.png)


After
![image](https://user-images.githubusercontent.com/108038989/181281562-294421cb-520d-47ba-b1bc-78809a90c1fe.png)




### 7. How does replacing the ninth-grade scores affect math and reading scores by school type?

Before:
![image](https://user-images.githubusercontent.com/108038989/181282118-4027e376-c7f6-4cda-a5f6-a9525a02dad6.png)


After:
![image](https://user-images.githubusercontent.com/108038989/181281739-086570fb-a1bd-4690-bcc8-545065a971d6.png)



## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


