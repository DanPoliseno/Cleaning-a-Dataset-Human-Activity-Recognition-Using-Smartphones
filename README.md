# Cleaning a Dataset: Human Activity Recognition Using Smartphones

UCI Machine Learning Repository: Human Activity Recognition Using Smartphones Data Set
Abstract: Human Activity Recognition database built from the recordings of 30 subjects performing 
activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Data:

'README.txt'

'features_info.txt': Shows information about the variables used on the feature vector.

'features.txt': List of all features.

'activity_labels.txt': Links the class labels with their activity name.

'train/X_train.txt': Training set.

'train/y_train.txt': Training labels.

'test/X_test.txt': Test set.

'test/y_test.txt': Test labels.


I will create one R script called run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the 
average of each variable for each activity and each subject.
