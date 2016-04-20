Code Book | Tidy.txt

Summary

This code book describes the contents of the clean data file "Tidy.txt" and the transformative steps that have been applied by "run_analysis.R" on the original data files contained in the folder "UCI HAR Dataset" in order to acheive said clean data.

participants: The identifier of an individual for whome data is available, a person who has taken part in the trial.
activities: The name of the activity the individual was performing at the point the data was collected.
The following variables (mean,std,mad,max,sma,energy,iqr,entropy,arcoeff,correlation) are captured from the three points of the accelerometer, X, Y and Z by participants and activities.

timeBodyAccelerator
timeGravityAccelerator
timeBodyAcceleratorJerk
timeBodyGyroscope
timeBodyGyroscopeJerk
timeBodyAcceleratorMagnitude
timeGravityAcceleratorMagnitude
timeBodyGyroscopeMagnitude
frequencyBodyAccelerator
frequencyBodyAcceleratorJerk
frequencyBodyGyroscope
frequencyBodyAcceleratorMagnitude
frequencyBodyBodyAcceleratorJerkMagnitude
frequencyBodyBodyGyroscopeMagnitude
frequencyBodyBodyGyroscopeJerkMagnitude



The Data | Tidy.txt

The body of the data set contains clean summarised data for an individual. The file consolidates the data contained in the test and train data contained the "UCI HAR Dataset" folder. The individual files within test have been joined together, as have the indivudual files within train, the resulting joined data has then been merged, appended, to build a complete data set for all participants and activities.




