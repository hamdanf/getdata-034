---
title: "ReadMe"
author: "Firas Hamdan"
22 Nov 2015
---

Data Download
=============
Raw Data could be downloaded using the following code:


```
## Download data file from web
temp <- tempfile() ## create temp file
download.file("https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip",temp) ## download zip file
unzip(temp) ## unzip file
rm(temp) ## remove temp file
```

Data Processing
============
"run_analysisR" is used to load data, clean it and generate the final data ser tidy_data.txt

