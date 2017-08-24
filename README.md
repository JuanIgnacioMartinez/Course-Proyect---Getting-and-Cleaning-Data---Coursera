# Course Proyect: Getting and Cleaning Data
Week 4 

This is the final course project of the course. My final script "run_analysis.R" does the following:

# Description: 

1)  Download the target dataset. If it already exist in the working directory, it dosent download it again).
2)  Load the activity and feature info, and after that both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4)  Loads the activity and subject data for each dataset for later merge those columns with the dataset
5)  Merges the two datasets
6)  Transform activity and subject columns into factors
7)  Creates a tidy dataset that consists of the average value of each variable for each subject and activity pair.
8)  Result are written in the file tidy.txt.
