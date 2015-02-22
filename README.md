Getting and Cleaning Data Course Project
========================================
This file describes how run_analysis.R script works.
* First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
* Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
* Second, use source("run_analysis.R") command in RStudio.
* Third, you will find two output files are generated in the current working directory:
- tidydata.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.
* Finally, use data <- read.table("tidydata.txt") command in RStudio to read the file.
