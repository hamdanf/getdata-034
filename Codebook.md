---
title: "Codebook"
author: "Firas Hamdan"
22 Nov 2015
---


Experimental design and background:

Raw Data (8 files):
        3 training files
        3 testing files
        1 features file
        1 activity name file


Processed Data:
        The Raw Data was processed as follows:
        1. Training and testing files were merged together.
        2. Variables with mean/SD were subseted.
        3. The activities were renamed to be descriptive.
        4. Variable names were cleaned.
        5. Final tidy dataset was created.
        

Variables:
        1. Two new variables were "Subject" and "activity".
        2. Variables that did not have mean/SD were removed.
        
List of variables
        Subject - Integer between 1 and 30 representing the subjects in the data
        Activity - One of six activities performed by the subjects including 
        
        Below variables are all the mean of the means or standard deviations of the raw accelerometer data
        
        time.BodyAcc.mean.X
        time.BodyAcc.mean.Y
        time.BodyAcc.mean.Z
        time.BodyAcc.std.X
        time.BodyAcc.std.Y
        time.BodyAcc.std.Z
        time.GravityAcc.mean.X
        time.GravityAcc.mean.Y
        time.GravityAcc.mean.Z
        time.GravityAcc.std.X
        time.GravityAcc.std.Y
        time.GravityAcc.std.Z
        time.BodyAccJerk.mean.X
        time.BodyAccJerk.mean.Y
        time.BodyAccJerk.mean.Z
        time.BodyAccJerk.std.X
        time.BodyAccJerk.std.Y
        time.BodyAccJerk.std.Z
        time.BodyGyro.mean.X
        time.BodyGyro.mean.Y
        time.BodyGyro.mean.Z
        time.BodyGyro.std.X
        time.BodyGyro.std.Y
        time.BodyGyro.std.Z
        time.BodyGyroJerk.mean.X
        time.BodyGyroJerk.mean.Y
        time.BodyGyroJerk.mean.Z
        time.BodyGyroJerk.std.X
        time.BodyGyroJerk.std.Y
        time.BodyGyroJerk.std.Z
        time.BodyAccMag.mean
        time.BodyAccMag.std
        time.GravityAccMag.mean
        time.GravityAccMag.std
        time.BodyAccJerkMag.mean
        time.BodyAccJerkMag.std
        time.BodyGyroMag.mean
        time.BodyGyroMag.std
        time.BodyGyroJerkMag.mean
        time.BodyGyroJerkMag.std
        freq.BodyAcc.mean.X
        freq.BodyAcc.mean.Y
        freq.BodyAcc.mean.Z
        freq.BodyAcc.std.X
        freq.BodyAcc.std.Y
        freq.BodyAcc.std.Z
        freq.BodyAcc.meanFreq.X
        freq.BodyAcc.meanFreq.Y
        freq.BodyAcc.meanFreq.Z
        freq.BodyAccJerk.mean.X
        freq.BodyAccJerk.mean.Y
        freq.BodyAccJerk.mean.Z
        freq.BodyAccJerk.std.X
        freq.BodyAccJerk.std.Y
        freq.BodyAccJerk.std.Z
        freq.BodyAccJerk.meanFreq.X
        freq.BodyAccJerk.meanFreq.Y
        freq.BodyAccJerk.meanFreq.Z
        freq.BodyGyro.mean.X
        freq.BodyGyro.mean.Y
        freq.BodyGyro.mean.Z
        freq.BodyGyro.std.X
        freq.BodyGyro.std.Y
        freq.BodyGyro.std.Z
        freq.BodyGyro.meanFreq.X
        freq.BodyGyro.meanFreq.Y
        freq.BodyGyro.meanFreq.Z
        freq.BodyAccMag.mean
        freq.BodyAccMag.std
        freq.BodyAccMag.meanFreq
        freq.BodyBodyAccJerkMag.mean
        freq.BodyBodyAccJerkMag.std
        freq.BodyBodyAccJerkMag.meanFreq
        freq.BodyBodyGyroMag.mean
        freq.BodyBodyGyroMag.std
        freq.BodyBodyGyroMag.meanFreq
        freq.BodyBodyGyroJerkMag.mean
        freq.BodyBodyGyroJerkMag.std
        freq.BodyBodyGyroJerkMag.meanFreq
        angle.tBodyAccMean.gravity.
        angle.tBodyAccJerkMean..gravityMean.
        angle.tBodyGyroMean.gravityMean.
        angle.tBodyGyroJerkMean.gravityMean.
        angle.X.gravityMean.
        angle.Y.gravityMean.
        angle.Z.gravityMean.

