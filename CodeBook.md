Project CodeBook.

1. Directory.
Source of data is "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
My working Directory is "C:/Users/user/Desktop/gettingandcleaning"

2. Variables.
Activity* : for Y_* text(* means, in this case, test and train)
Subject* : for Subject_* text
Features* : for X_* text
Any other Variables like, DataSubject, DataActivity, DataFeatures,,, are temporary Variables
Variable "Data" is the final Data for tidy Data.

3. Function.
dir, download, unzip : for Downloading and Unzip the file
Read and Write : for input and output Data form Rstudio
rbind, cbind : for marge data
names, grep, Factor, gsub : Naming and Rearrange the Data

Finally, Make file "tidydata.txt"
