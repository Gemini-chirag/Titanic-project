## Titanic Dataset Analysis
 ## Overview
 This repository contains an analysis of the Titanic dataset, focusing on survival rates among different groups of passengers. 
 The Titanic dataset provides information about the passengers aboard the RMS Titanic, which tragically sank on April 15, 1912. 
 The analysis aims to uncover insights into survival rates based on various features such as ticket class, sex, age, and more.

## Dataset
The Titanic dataset includes the following features:

survival: Survival status (0 = No, 1 = Yes)
pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
sex: Sex (0 = Female, 1 = Male)
Age: Age in years
sibsp: Number of siblings/spouses aboard the Titanic
parch: Number of parents/children aboard the Titanic
ticket: Ticket number
fare: Passenger fare
cabin: Cabin number
embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Key Insights and Analysis
1. Difference in Mean Sex Between Survived and Not Survived Passengers
Objective: Determine if there is a significant difference in the mean sex (represented as 0 for female and 1 for male) between passengers who survived and those who did not.
Method: Use statistical tests to compare the mean sex of the two groups (survived vs. not survived).
2. Survival Rate Difference Between Male and Female Passengers
Objective: Examine if there is a substantial difference in the survival rate between male and female passengers.
Method: Calculate the survival rates for male and female passengers and use statistical tests to determine the significance of the difference.

## Analysis Steps
## Data Preprocessing
Load the dataset and handle any missing values.
Convert categorical variables into numerical ones where necessary, particularly for the sex column.

## Exploratory Data Analysis (EDA)
Generate summary statistics for key features.
Visualize the distribution of survival rates based on different features.

## Statistical Analysis
Perform t-tests to compare the mean sex between passengers who survived and those who did not.
Calculate and compare survival rates between male and female passengers using chi-square tests.



![this-terrible-scene-painted-by-german-artist-willy-stoewer-news-photo-517357578-1545065377](https://github.com/Gemini-chirag/Titanic-project/assets/172970150/a688ab72-44f1-4d49-aeb1-ee7a5523371c)
