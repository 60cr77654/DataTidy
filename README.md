# DataTidy

---

# Here are the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# Analysis method

These are the steps used to produce the tidy data set, as coded in the run_analysis.R script.

Load the tidyverse library

Make a path to the main project directory

Make new feature labels

Read in the test set and apply feature labels

Read in the activities and subjects, and bind them to the test set

Narrow the test set

Read in the train set and apply feature labels

Read in the activities and subjects, and bind them to the train set

Narrow the train set

Merge the test and train sets

Convert the digits in the activity column into the correct words

Calculate and store the average of each feature for each activity and each subject

Write the tidy data set to disk

# Script
run_analysis.R performs the analysis and generates the tidy data set. No other scripts are required.
