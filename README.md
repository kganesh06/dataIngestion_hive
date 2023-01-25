# Data Ingestion in Hive using Sqoop

**Introduction**

Implemented all the steps which required to ingest the data from Relation Database to Hive.

**Business Rrequirement**

Perform data ingestion pipiline : HDFS --> MySQL --> Hive using Apache Sqoop.

**It Covers **

1. MySQL

2. Sqoop (Import, Export and Sqoop Job)

3. Hadoop-Linux commands

4. Hive (Hive statements, Partition, Bucketing and Compression technique)



Listed the steps below to ingest data from MySQL to Hive.



1. Create Required directories in HDFS using hdfs-linux commands and Load the data into HDFS.

2. Create Staging and Actual tables in MySQL.

3. Uploade the data into MySQL tables using Sqoop Export.

4. Create Sqoop jobs to import data from MySQL to HDFS.

5. Create External tables in Hive on top of data in HDFS.

6. Create directories in HDFS for dynamice partitions.

7. Create Optimized tables in Hive.

8. Insert data from normal hive tables to optimized hive tables.

9. Perform Optimization on query level.

10. Analyse the data based on requirements.

