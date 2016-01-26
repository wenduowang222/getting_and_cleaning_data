#contact the author: wenduo.wang@hotmail.com
This repository contains the codes and data for the capstone project of Getting and Cleaning Data course.
The original data was downloaded via https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The descriptions of the documents are listed below
run_analysis.R:		the R script that performs transformation and computing on the downloaded original data,
					resulting in the final output data set "average.txt".
average.txt:		the output data set summarising the mean values of "mean()" and "std()" sensor statistics of each subject and activity.
UCI HAR Dataset/:	the downloaded original data folder, yet the "Inertial Signals" subdirectories have been removed
					for they are not directly related to the subsequent transformation.
					For its original descriptions please refer to "UCI HAR Dataset/README.txt".

More Details
run_analysis.R:		the explanation of transformation and computing is commented in the code.
average.txt:		the dataset contains 68 columns. The first 2 columns are subject id and activity, followed by the 66 columns of mean of sensor statistics.
					For more definition of the statistics, please refer to "UCI HAR Dataset/features_info.txt"