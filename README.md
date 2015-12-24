## Getting-and-Cleaning-Data

Project for course Getting and Cleaning Data offered by Coursera

The script Run_Analysis.R requires all the data files to be unzipped into the working directory or R. The new tidy data set is generated in the same folder. This is the following problem statement:

<i>The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected. </i>

The script run_analysis.R does the following: 

* Reads all the data from the zipped folder into appropriate variables.
* Assigns proper column names to the data stored in the above variables
* Merges the training and test sets to create a 'finalData' dataset.
* Creates a logical vector that marks all the columns having mean(), std() as TRUE and the rest as FALSE
* Subsets the 'finalData' dataset on this logical vector so that the updated'finalData' data set only contains the readings for mean() and std()
* Assigns proper labels to the columns in the 'finalData' dataset
* Creates a 'tidyData' data set with the updated values

