# Getting And Cleaning Data

## Course Project

You should create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to perform to use this script:

1. Download data source into folder 'UCI HAR Dataset'.
2. Put 'run_analysis.R' in main folder of 'UCI HAR Dataset'. Set this as the working directory.
3. Run `source("run_analysis.R")` and it will generate a new file `tiny_data.txt` in the working directory.
