Getting-and-Claning-DataCourse-Project

## Created a script with below actions

## Below command is to set the working directory where all txt files are stored.

## Create subject_test data frame to store data from subject_test.txt file. It has 1 column and 2947 rows

## Create activity_test data frame to store data from y_test.txt file. It has 1 column and 2947 rows

## Crate feature vector data frame for test subjects from X_test.txt file. It has 561 columns and 2947 rows

## Create a single test data frame to combine test subjects, activities and feature vector. It has 563 columns and 2947 rows

## Create subject_train data frame to store data from subject_train.txt file. It has 1 column and 7352 rows

## Create activity_train data frame to store data from y_train.txt file. It has 1 column and 7352 rows

## Crate feature vector data frame for train subjects from X_train.txt file. It has 561 columns and 7352 rows

## Create a single train data frame to combine train subjects, activities and feature vector. It has 563 columns and 7352 rows

## for easy data frame handling work in dplyr; get the dplyr library fist 

## Convert test and train data frames using tbl_df() command

## Below part of the scripts combines test and train data to generate complete_data

## Give proper names to all columns

## Below scrip is to select columns that contain either mean or dev

## extract subject and activity coulmns

## combine above created datasets
        
## Below script is created to add the activity name column
##sort the data frame on subject, activity and activity name
## group by using subject, activity and activity name
## get the mean of all columns





