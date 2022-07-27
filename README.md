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

The DataFrames below display the results before and after replacing the Thomas High School ninth grade math and reading scores with NaNs values.

### 1. How is the district summary affected?

#### School District Summary Before:
![ds1](https://user-images.githubusercontent.com/108038989/181275088-2d3509c6-4a54-4aca-a902-aad2197abbbb.png)

#### School District Summary After:
![ds2](https://user-images.githubusercontent.com/108038989/181275547-ef4cea38-a8a2-413f-ba44-5ea0c2a2f78f.png)

### 2. How is the school summary affected?

#### School Summary Before:
![Screenshot 2022-07-27 112534](https://user-images.githubusercontent.com/108038989/181286761-54f57244-1df5-4c9f-9900-5fc5be2e928b.png)

#### School Summary After:
![Screenshot 2022-07-27 112343](https://user-images.githubusercontent.com/108038989/181286364-5c38c9e2-2dca-4477-a073-569d02c56838.png)

### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

#### Top 5 Performing Schools Before:
![181282914-b1b2dc3f-6318-4af4-8fd2-adc741db6d16](https://user-images.githubusercontent.com/108038989/181291587-771e9ca1-b38b-4bf4-b0a9-12f8f2cfdea9.png)

#### Top 5 Performing Schools After:
![after](https://user-images.githubusercontent.com/108038989/181291652-c50d0b30-fca0-487f-ac7a-4ae617808078.png)

#### Bottom 5 Performing Schools Before: 
![image](https://user-images.githubusercontent.com/108038989/181283055-702f18d3-4c4c-44c0-825f-eec536c341ed.png)

#### Bottom 5 Performing Schools After:
![image](https://user-images.githubusercontent.com/108038989/181278469-6c81bbdf-a59a-46c3-a3cd-7628cad42d32.png)

### 4. How does replacing the ninth-grade scores affect math and reading scores by grade?

#### Math Scores Before:
![math before](https://user-images.githubusercontent.com/108038989/181292576-3893e1df-b1ad-4017-8067-b1cbabd1f87f.png)

#### Math Scores After:
![math after](https://user-images.githubusercontent.com/108038989/181292588-dc731324-2aac-41b3-b17b-790e6d47b8a3.png)

#### Reading Scores Before:
![reading before](https://user-images.githubusercontent.com/108038989/181292602-3f47bdfb-2667-47e1-b60f-65e8b9e5ff4b.png)

#### Reading Scores After: 
![reading after](https://user-images.githubusercontent.com/108038989/181292619-872e543a-fca6-4572-b157-718ed87600d0.png)

### 5. How does replacing the ninth-grade scores affect math and reading scores by school spending?

#### School Spending Before:
![image](https://user-images.githubusercontent.com/108038989/181282546-4e00e66a-d77e-4501-9a02-2ab3cea726de.png)

#### School Spending After:
![image](https://user-images.githubusercontent.com/108038989/181281085-9c96937b-d6da-4569-974e-ddee49ed97c5.png)

### 6. How does replacing the ninth-grade scores affect math and reading scores by school size?

#### School Size Before: 
![image](https://user-images.githubusercontent.com/108038989/181282227-2b357ddf-b4f8-44f8-8a6a-98df2c4f5fd3.png)

#### School Size After: 
![image](https://user-images.githubusercontent.com/108038989/181281562-294421cb-520d-47ba-b1bc-78809a90c1fe.png)

### 7. How does replacing the ninth-grade scores affect math and reading scores by school type?

#### School Type Before:
![image](https://user-images.githubusercontent.com/108038989/181282118-4027e376-c7f6-4cda-a5f6-a9525a02dad6.png)

#### School Type After:
![image](https://user-images.githubusercontent.com/108038989/181281739-086570fb-a1bd-4690-bcc8-545065a971d6.png)

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


