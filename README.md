# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity and feature info
3. Load both the training and test data sets, keeping only those columns which
   reflect a mean or standard deviation
4. Load the activity and subject data for each data set, and merge those
   columns with the data set
5. Merge the training and test data sets
6. Convert the `activity` and `subject` columns into factors
7. Creates a tidy data set that consists of the average (mean) value of each
   variable for each subject and activity pair

The final result is shown in the file `FinalData.txt`.