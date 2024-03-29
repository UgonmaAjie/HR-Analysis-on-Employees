# Introduction

The aim of this project is to exhibit my skills in analyzing and visualizing Human Resource (employees)
data with user friendly navigation using Power BI.
Data was downloaded as a csv file, and extracted into Power BI for cleaning, analysis and visualization.
The Report consists of three pages:

- Home
- Action
- Detail

## Problem Statement

- To analyse and visualize employees , 
- Those due for promotion or to be laid off
- Length of Service in organization
- Total Employee by the different levels


## Data transformation/Cleaning
Data was efficiently cleaned and transformed with the Power Query Editor of Power BI.
- Removing missing values 
- Removing Duplicates 
- Converting to different data types
- Creating Dax measures

## Data Modeling 
Power BI automatically connected related tables resulting in a star schema model. THe 'HR Analytics data' table is the 
fact table of the model. The only dimension table is the 'HR employee data' table which is connected to the HR Analytics data table via the common 
column 'EmployeeNumber.

## Visualization

_Report showing the number of employees, their levels and those either due for promotion or to be laid off_

![](HR_1.JPG)

_Report showing the names of the employees that are to be promoted or laid off_
![](HR_2.JPG)

_Report showing the number of employees in their different department and roles_
![](HR_3.JPG)

## Analysis 
The report accurately measures the satisfaction of the employees and probably because incentives like promotion isn't awarded 
even when due. The number of employees to be laid off are higher than those due for promotion which led to low job satisfaction.

This report identifies the problematic area , with the goal of encouraging employees. 
