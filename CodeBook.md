## Getting and Cleaning Data - peer graded project


## The original dataset was transformed by  
1. Creating a single data set by combining the training and test sets.
2. Extracting only the mean and standard deviation measurements for each measurement.
3. Naming the activities in the data set using descriptive activity names
4. Labeling the data collection appropriately with descriptive activity titles.
5. Make a separate tidy data set containing the average of each variable for each activity and subject.

## About the R script
File with R code "run_analysis.R" has 5 following steps in accordance to the assigned task of course work

## About the variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in
