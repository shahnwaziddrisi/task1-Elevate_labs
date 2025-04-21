# task1-Elevate_labs
I used the *Big mart Sales Dataset* and some cleaning on it
things i did where:
1.Removed the duplicate values from the ID table as ID should be unique,no two id's can be same.
2.Filled the missing values by taking the average in the  item_weight column and used mode in order to fill the outlet_size column.
The reason to use MEAN for item_weight was that the data was fairly normal(no outliners).Also as the missing values were alot ,we cannot simply drop all the rows.
3.since LF and low Fat was the same thing ,replaced it with proper naming of Low fat.Similarly did the same for reg and Regular to Regular Fat
4.Converted all the data to  its  desired format.
5.Made it more specific in outlet_type column by replacing the values.

Since the overall idea of cleaning and standardising the dataset is to make it more meaninful,So i gave meaningful names to specific columns so that i would become easy for someone to understand the data properly and make the best use of it. 
