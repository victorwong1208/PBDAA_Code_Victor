# PBDAA_Code_Victor

READ ME BY Victor Wong(zw2047) at NYU CS 476 PBDAA With Prof. Malavet

Everything is in dataproc hw10 folder, permission granted.

For each job, I included input, output, and the code.

For each file, I only included input, and output files, since some codes are run on HIVE

However, since datas are too big to be uploaded for my teammate, in his file, I will only upload the code and screen shots. From his end, he analyzed the sales data and combine it with my complaints data, while I get to further analyze the data. Therefore we will have our combined data ready as joinedoutput.csv for analysis.

At the same time, for HIVE, please follow the instruction to upload the data from the corresponding file. For profiling, I have MapReduce -- counting the rows of the file as a part of data ingesting, and HIVE -- producing basic values for the complaints data alone to valid the data quality

For data ingesting, please run the MapReduce job on the code and you will get the same output

After that, please run the PROFILING MapReduce job on the code and you will find out the profiling data of the ingested data

For cleaning, please follow the code to reproduce the HIVE query.

After that, please run the HIVE Profiling query to get some more initial data from the cleaned HIVE table

After that, please ingest, profile, and clean the other dataset(under the folder Javae) -- for data uploading purpose, I only include the original data of the other sale dataset
