# Biopharmaceutical-Manufacturing-Execution-System-MES-
Biopharmaceutical Manufacturing Execution System (MES)
etl process:
1).get all streaming data in json format 
2).valid the raw data and then load to csv file, csv file will be split into files based on date
3).store the streaming data into dataframe and do the calculations
4).valid and test the aggregated data and store all the data to csv file
5).delete the finished experiment to save space
6).update the input and output valve status
