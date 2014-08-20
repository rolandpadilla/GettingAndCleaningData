GettingAndCleaningData
======================
You should create one R script called run_analysis.R that does the following:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

In order to run the file into Rstudio, you would have to set the root folder as a working directory and run source("run_analysis.R", local=T)

The merged data sets are stored under "users_moves". The extracted data set with the mean and standard deviation is stored under "extract."
The tidy data set with the average of the variables for each activity and each subject is under the working directory "tidyDataSet.txt"
