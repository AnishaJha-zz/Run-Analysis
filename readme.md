---
title: "readme.md"
author: "Anisha"
date: "20 September 2014"
output: html_document
---
This is the ReadMe of the script run_analysis.R

<ul>
<li>Start directory is created and data.zip is downloaded from the given fileURL into a new directory project data</li>
<li>Data is extracted in the directory project data</li>
<li>A list of directories is got in extractedDirs</li>
<li>A combined directory is created which  the data of both test and train</li>
<li>combinedirList contains the list of directories to be created</li>
<li>Merge the datasets of files in test and train directories</li>
<li>Create files in combine directory and write by reading from datasets</li>
<li>Read files containing subject,activity and activity labels</li>
<li>Create columns for descriptive activities in dfcol_activitylabels</li>
<li>Get variable names from features.txt into df_features</li>
<li>Descriptive variable names is got from X_combine.txt and put into df_rawdata</li>
<li>Grep for variable names containing mean and std from df_features</li>
<li>Select variable names from df_feature</li>
<li>Select the data from df_rawdata</li>
<li>Create a data table with descriptive activity labels for the selected data</li>
<li>Create a data table with average of each activity and each subject as tbl_final2</li>
</ul>
