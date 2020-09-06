# Getting-and-Cleaning-Data-Course-Project
This are my results about the getting and cleaning data course project.

First of all, I set the work directory to start to work with the data set, de directory where y can find the files to be read.
After reading the data, I merge the datasets whir rbind command to merge the training and test sets on one dataset.

To extract measurments on the mean and sd, I select all columns using the grep command with a regular expression. 
I use the file activity_labels.txt to extract the activity names.
