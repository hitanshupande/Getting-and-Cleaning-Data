##Introduction

This codebook contains descriptions related to the project work carried out as part of the Coursera offering Getting and Cleaning Data. It contains variable description and transformations carried out to arrive at a clean data set in `tidy.txt`.

## Variables
* `features`
* `activityType`
* `subjectTrain`
* `xTrain`
* `yTrain`
* `subjectTest`
* `xTest`
* `yTest`
* `finalData`
* `tidyData`

## Identifiers

* `subject` - The ID of the test subject
* `activity` - The type of activity performed when the corresponding measurements were taken

## Activity Labels

* `WALKING` (value `1`): subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
* `SITTING` (value `4`): subject was sitting during the test
* `STANDING` (value `5`): subject was standing during the test
* `LAYING` (value `6`): subject was laying down during the test

## Transformations

* `Step 1` Merges the training and the test sets to create one data set.
* `Step 2` Extracts only the measurements on the mean and standard deviation for each measurement. 
* `Step 3` Uses descriptive activity names to name the activities in the data set
* `Step 4` Appropriately labels the data set with descriptive variable names. 
* `Step 5` From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

