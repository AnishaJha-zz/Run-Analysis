---
title: "readme.md"
author: "Anisha"
date: "21 October 2014"
output: html_document
---
This is the ReadMe of the script run_analysis.R

<ul>
<li>Working directory is set</li>
<li>Start directory data is created and data.zip is downloaded from the given fileURL into a new directory project data</li>
<li>Data is extracted in the directory data</li>
<li>features.txt is cleaned up and read into data frame features_cleaned</li>
<li>feature names is got from features_cleaned</li>
<li>Create a vector varnames containing the variable names of the combined data set.</li>
<li>Load the files X_train.txt, X_test.txt and combine using rbind</li>
<li>Repeat for subject train and Y files </li>
<li>Combine the above three row binded data sets into combined_df data frame</li>
<li>Give names to the columns of combined_df</li>
<li>Extract the required variables of mean and standard deviation into selected_df</li>
<li>Each activity is labelled with descriptive activity labels.</li>
<li>Giving descriptive names to the variables in data set.</li>
<li>Melted the data set using melt for subject and actlabel </li>
<li>Created tidy data set using dcast</li>
<li> Written out tidy data set to a .csv file</li>
</ul>
