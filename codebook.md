Codebook
The purpose of this project is to merge datasets, tidy them, and create a final text file.
Data found at: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Variables

The following variables are for reading the various data in the tables

x_train
y_train
subject_train
x_test
y_test
subject_test
features
activityLabels

The following variables are for renaming columns
colnames(x_train)
colnames(y_train)
colnames(subject_train)
colnames(x_test)
colnames(y_test)
colnames(subject_test)
colnames(activityLabels)

The following variables merge and rename the data
mrg_train
mrg_test
setAllInOne
colNames

The following variables extract mean and std data and merge columns
mean_and_std
setForMeanAndStd
setWithActivityNames

secTidySet is the final datasest, which is also written as a text file.