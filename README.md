Getting-and-Claning-DataCourse-Project
Created a script with below actions
1) Below command is to set the working directory where all txt files are stored.
2) Create subject_test data frame to store data from subject_test.txt file. It has 1 column and 2947 rows
3 Create activity_test data frame to store data from y_test.txt file. It has 1 column and 2947 rows
4) Crate feature vector data frame for test subjects from X_test.txt file. It has 561 columns and 2947 rows
5) Create a single test data frame to combine test subjects, activities and feature vector. It has 563 columns and 2947 rows
6) Create subject_train data frame to store data from subject_train.txt file. It has 1 column and 7352 rows
7) Create activity_train data frame to store data from y_train.txt file. It has 1 column and 7352 rows
8) Crate feature vector data frame for train subjects from X_train.txt file. It has 561 columns and 7352 rows
9) Create a single train data frame to combine train subjects, activities and feature vector. It has 563 columns and 7352 rows
10) for easy data frame handling work in dplyr; get the dplyr library fist 
11) Convert test and train data frames using tbl_df() command
12) Below part of the scripts combines test and train data to generate complete_data
13) Give proper names to all columns
14) Below scrip is to select columns that contain either mean or dev
15) extract subject and activity coulmns
16) combine above created datasets
17) Below script is created to add the activity name column
18) sort the data frame on subject, activity and activity name
19) group by using subject, activity and activity name
20) get the mean of all columns





