Coding Steps:

1. Load the necessary packages to import the dataset and then clean it.
    1.1 we are using data.table and reshape2 packages. 
    1.2 we download the zip dataset and unzip it next. 
    
2. We use fread function to read activity_labels and features files.
    2.1 We then extract only the measurements on the mean and standard deviation for each measurement using regular expressions.

3. Next we load the training and test datasets after step 2. 

4. Next we merge the training and test datasets to create one single dataset. 

5. After merging we take that dataset and create a single, independent tidy data set with the average of each variable for each activity and each subject.

6. The name of the resulting tidy data is "tidyData.txt". 
