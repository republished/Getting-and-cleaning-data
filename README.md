# Getting-and-cleaning-data
The R script, run_analysis.R, does the following:

	1. Download the dataset if it does not already exist in the working directory
	2. Load the activity and feature info
	3. Loads both the training and test datasets, keeping only mean or standard deviation measurements
	4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
	5. Merges the two datasets
	6. Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
