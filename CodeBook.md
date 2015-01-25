---
title: "Coursera Getting and Cleaning Data Project Code Book"
author: "Makarand Shivadevuni"
date: "January 23, 2015"
output: html_document
---
This file describes how run_analysis.R script works.

* Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  and rename the folder with "dataset".
* Make sure the folder "dataset" and the run_analysis.R script are both in the current working directory.
* Use source("run_analysis.R") command in RStudio.
* Find two output files "merged_data.txt" and "data_with_means.txt" that are generated in the current working directory:
*  Use data <- read.table("data_with_means.txt") command in RStudio to read the file.