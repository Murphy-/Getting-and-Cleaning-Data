Getting-and-Cleaning-Data
=========================
Project Objectives:

You should create one R script called run_analysis.R that does the following. 
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

Steps:

1. Download and unzip the source into a folder on your local drive, say C:\Users\yourname\Documents\R\

2. Copy run_analysis.R to C:\Users\yourname\Documents\R\UCI HAR Dataset\

3. in RStudio: setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\") and then: source("run_analysis.R")

4. The script normally runs for ~30 seconds, but the exact number depends on your system.

5. Use data <- read.table("data_set_with_the_averages.txt") to read the latter. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30*6=180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files
