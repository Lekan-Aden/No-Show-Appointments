# Investigating No-Show Appointments

## Introduction
In this project, I will be using the No-Show Appointments [dataset](https://www.google.com/url?q=https://www.kaggle.com/joniarroba/noshowappointments&sa=D&ust=1532469042118000) obtained from kaggle. It contains 110,527 medical appointments in Brazil with 14 attributes, and includes information regarding whether or not patients showed up for the scheduled appointment. My goal in this project is to "investigate" this data using **pandas**, **numpy**, **matplotlib**, and **seaborn** to output descriptive statistics and visuals that reveal insights and trends.

## Pre-Analysis: Data Cleaning
To ensure my analysis was free of errors, I did some cleaning on the data, including changing some variable data types, renaming variables, checking for missingness and duplicates, and removing observations with incorrect data. 

## Summary of Key Findings
There is an almost identical proportion of males(80%) and females (79.7%) who showed up for their appointments. These proportions are indeed very close, and it may well be that the difference between them is only due to random chance. Establishing whether this difference is significant can be done via hypothesis testing, though, that is outside the scope of my analysis. I also found out that appointment dates farther in the future made a patient less likely to show up. While older patients are more committed to their appointments--particularly those who are 45 years and above--younger patients are not as committed. Finally, most of the patients with hypertension and diabetes are older patients, often above 50 years of age.
