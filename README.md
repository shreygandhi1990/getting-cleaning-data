Getting and Cleaning Data
Course Project

The script run_analysis.R does the following.

  i. Merges the training and the test sets to create one data set.
  ii.  Extracts only the measurements on the mean and standard deviation for each measurement.
  iii.  Uses descriptive activity names to name the activities in the data set
  iv.  Appropriately labels the data set with descriptive activity names.
  v.  Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Steps to work on this course project

    Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
    Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
    Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

Dependencies

 It depends on reshape2 and data.table
