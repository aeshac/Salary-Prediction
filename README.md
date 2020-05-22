# Salary-Prediction

This repository contains Python scripts to analyse the salary data which helps predict the salaries for newer job postings

## Goal
> Build a model to predict the salaries of job postings 

## Dataset Information
#### Total 3 csv files are used
#### 1. train_features.csv: Each row represents metadata for an individual job posting.

<class 'pandas.core.frame.DataFrame'>

RangeIndex: 1000000 entries, 0 to 999999

Data columns (total 8 columns):

 #|Column|Non-Null|Count|Dtype 
---|------|---------|-----|-----
 0|jobId|1000000|non-null|object
 1|companyId|1000000|non-null|object
 2|jobType|1000000|non-null|object
 3|degree|1000000|non-null|object
 4|major|1000000|non-null|object
 5|industry|1000000|non-null|object
 6|yearsExperience|1000000|non-null|int64 
 7|milesFromMetropolis|1000000|non-null|int64 
 
dtypes: int64(2), object(6)

memory usage: 61.0+ MB

#### 2. test_features.csv: Similar to train_features.csv, each row represents metadata for an individual job posting.

<class 'pandas.core.frame.DataFrame'>

RangeIndex: 1000000 entries, 0 to 999999

Data columns (total 8 columns):

 #|Column|Non-Null|Count|Dtype 
---|------|---------|-----|-----
 0|jobId|1000000|non-null|object
 1|companyId|1000000|non-null|object
 2|jobType|1000000|non-null|object
 3|degree|1000000|non-null|object
 4|major|1000000|non-null|object
 5|industry|1000000|non-null|object
 6|yearsExperience|1000000|non-null|int64 
 7|milesFromMetropolis|1000000|non-null|int64 
 
dtypes: int64(2), object(6)

memory usage: 61.0+ MB

#### 3. train_salaries.csv: Each row associates a “jobId” with a “salary”.

<class 'pandas.core.frame.DataFrame'>

RangeIndex: 1000000 entries, 0 to 999999

Data columns (total 2 columns):

 #|Column|Non-Null|Count|Dtype 
---|------|---------|-----|-----
 0|jobId|1000000|non-null|object
 1|salary|1000000|non-null|int64

dtypes: int64(1), object(1)

memory usage: 15.3+ MB

