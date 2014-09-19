Data source
===========
This dataset is derived from the "Human Activity Recognition Using Smartphones Data Set" which was originally made avaiable here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Feature Selection 
=================

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

The assignment states that only the mean and standard deviation for the measurements should be used. Hence the original data was cleaned and tidied up to get the final dataset below.

mean: Mean value
std : Standard deviation

Output File Columns
===================

subject              - ID indicating the subject from whom data was collected<br>
activity             - Activity being performed<br>
tbodyacc-mean-x<br>
tbodyacc-mean-y<br>
tbodyacc-mean-z<br>
tbodyacc-std-x<br>
tbodyacc-std-y<br>
tbodyacc-std-z<br>
tgravityacc-mean-x<br>
tgravityacc-mean-y<br>
tgravityacc-mean-z<br>
tgravityacc-std-x<br>
tgravityacc-std-y<br>
tgravityacc-std-z<br>
tbodyaccjerk-mean-x<br>
tbodyaccjerk-mean-y<br>
tbodyaccjerk-mean-z<br>
tbodyaccjerk-std-x<br>
tbodyaccjerk-std-y<br>
tbodyaccjerk-std-z<br>
tbodygyro-mean-x<br>
tbodygyro-mean-y<br>
tbodygyro-mean-z<br>
tbodygyro-std-x<br>
tbodygyro-std-y<br>
tbodygyro-std-z<br>
tbodygyrojerk-mean-x<br>
tbodygyrojerk-mean-y<br>
tbodygyrojerk-mean-z<br>
tbodygyrojerk-std-x<br>
tbodygyrojerk-std-y<br>
tbodygyrojerk-std-z<br>
tbodyaccmag-mean<br>
tbodyaccmag-std<br>
tgravityaccmag-mean<br>
tgravityaccmag-std<br>
tbodyaccjerkmag-mean<br>
tbodyaccjerkmag-std<br>
tbodygyromag-mean<br>
tbodygyromag-std<br>
tbodygyrojerkmag-mean<br>
tbodygyrojerkmag-std<br>
fbodyacc-mean-x<br>
fbodyacc-mean-y<br>
fbodyacc-mean-z<br>
fbodyacc-std-x<br>
fbodyacc-std-y<br>
fbodyacc-std-z<br>
fbodyaccjerk-mean-x<br>
fbodyaccjerk-mean-y<br>
fbodyaccjerk-mean-z<br>
fbodyaccjerk-std-x<br>
fbodyaccjerk-std-y<br>
fbodyaccjerk-std-z<br>
fbodygyro-mean-x<br>
fbodygyro-mean-y<br>
fbodygyro-mean-z<br>
fbodygyro-std-x<br>
fbodygyro-std-y<br>
fbodygyro-std-z<br>
fbodyaccmag-mean<br>
fbodyaccmag-std<br>
