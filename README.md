# Getting_and_Cleaning_Data_project
Coursera course by John Hospins University

Getting and Cleaning Data Course Project

About this Project（Instructions for Project）：
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set.
The goal is to prepare tidy data that can be used for later analysis.
You will be graded by your peers on a series of yes/no questions related to the project.
You will be required to submit:
1.	a tidy data set as described below
2.	a link to a Github repository with your script for performing the analysis, and
3.	a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This file explains how all of the scripts work and how they are connected.
One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
You should create one R script called run_analysis.R that does the following.
•	Merges the training and the test sets to create one data set.
•	Extracts only the measurements on the mean and standard deviation for each measurement. 
•	Uses descriptive activity names to name the activities in the data set
•	Appropriately labels the data set with descriptive activity names. 
•	Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 



What you find in this repository:
•	README.md: this file
•	CodeBook.md: information about raw and tidy data set and elaboration made to transform them
•	run_analysis.R: R script to transform raw data set in a tidy one
•	tidy.text: the results from running run_analysis.R
Data Raw:
•	'features.txt': List of all features.
•	'activity_labels.txt': List of class labels and their activity name.
•	'train/X_train.txt': Training set.
•	'train/y_train.txt': Training labels.
•	'train/subject_train.txt': ID's of subjects in the training data
•	'test/X_test.txt': Test set.
•	'test/y_test.txt': Test labels.
•	'test/subject_test.txt': ID's of subjects in the training data
A brief description of the script:
You should create one R script called run_analysis.R that does the following. 
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement. 
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive variable names. 
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


