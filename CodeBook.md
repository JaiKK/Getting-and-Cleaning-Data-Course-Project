###Variables
**fileURL** This contains the URL of data file to be downloaded  
**fileLocal** This contains data files local name  
**activity_labels** This contains data from file "activity_labels.txt"  
**features** This contains data from file "features.txt  
**subject_train** This contains data from file "subject_train.txt"  
**X_train** This contains data from file "X_train.txt"  
**y_train** This contains data from file "y_train.txt"  
**subject_test** This contains data from file "subject_test.txt"  
**X_test** This contains data from file "X_test.txt"  
**y_test** This contains data from file "y_test.txt"  

###Data 
**train_data** This will contain all the columns from X, Y and subject training data  
**test_data** This will contain all the columns from X, Y and subject test data  
**full_data** This will contains all the records of training and test data  
**mean_std_data** This will contains a subset of data for Mean and standard deviation columns, activityID, subjectID and activityType. This will also contain proper column names.  
**data_average** This will contains mean of all numeric columns  

###Transformations
1. For test and training data subject, activity and measurement details were giving in separate files. Thus activity for merging data performed.  
2. Column names were containing codes, parenthesis, hyphen, repeated words etc.  which are removed and replaced with underscore where applicable.  
3. Mean calculation for all numeric columns.  
4. Export data to a csv file "tidyData.csv"


