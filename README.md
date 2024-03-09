# Combine-datasets-by-columns
The code can combine two datasets by comparing the columns of 2 excel files and if the same column appears in both files, it will combine on those columns, if not then it will be empty.¶

It also considers that there are columns with similar meanings but different names, so it uses fuzzy matching library fuzzywuzzy to detect these columns.
For example in one file the column name 'flood_sev_nodamage' is called 'flood_sev_1' in the second file. But they are essentially the same columns with different names.
