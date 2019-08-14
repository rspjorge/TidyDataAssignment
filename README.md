# TidyDataAssignment
Getting and Cleaning Data Course Project - Coursera

## Modifications description
To perform the modifications, dplyr, data.table and tidyr libraries were used. The main steps are described below, but a detailed description is available within the run_analysis.md file.   

### Download
Script to download the zip file with all necessary text files from the following url:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

### Training and test sets were merged to create one data set.
For both Activity and Subject files, the script will merge the training and the test sets by row binding and rename variables "subject" and "activityNum".

### Only measurements on the mean and standard deviation extratracted for each measurement.
Reading "features.txt" and extracting only the mean and standard deviation

### Descriptive activity names used to name the activities in the data set
Enter name of activity into dataTable

### Data set appropriately labeled with descriptive variable names. 

### From the the previous steps, a second, independent tidy data set was created, with the average of each variable for each activity and each subject.
