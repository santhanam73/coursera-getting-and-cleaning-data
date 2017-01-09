# coursera-getting-and-cleaning-data
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set.


Steps for the Analysis:
1.Download the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
2.Load required packages
  library(dplyr)
  library(data.table)
  library(tidyr)
3.Files in folder ‘UCI HAR Dataset’ that will be used are:

    SUBJECT FILES
    test/subject_test.txt
    train/subject_train.txt
    ACTIVITY FILES
    test/X_test.txt
    train/X_train.txt
    DATA FILES
    test/y_test.txt
    train/y_train.txt
    features.txt - Names of column variables in the dataTable

    activity_labels.txt - Links the class labels with their activity name.
    
  4.Source run_analysis.R
  
  5.Executing the file would read the file and create TidyDataOutput.txt

