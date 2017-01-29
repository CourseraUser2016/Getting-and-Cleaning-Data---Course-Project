# Getting-and-Cleaning-Data---Course-Project

This is the course project for the Getting and Cleaning Data Coursera course. 

Download the dataset from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
Extract the dataset to the working directory 

The R script, run_analysis.R, does the following:
Load the activity and feature info
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.csv.  
