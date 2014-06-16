# Getting and Cleaning Data Project



## run_analysis.R



The cleanup script (run_analysis.R) does the following:


1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement. 

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive activity names. 

5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 



## Running the script


To run the script, source `run_analysis.R`.


## Cleaned Data



The resulting clean dataset is in this repository at: `tidyData.txt`. 
It contains one row for each subject/activity pair and columns for subject, activity, and each feature that was a mean or standard deviation from the original dataset.

