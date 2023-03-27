# CovidDataPipeline
Here I have tried to create a simple data pipeline using covid data. 
The data is ingested from mysql incrementally by creating sqoop jobs. Hive tables are created on the top of that, and partitioning and bucketing techniques are also implemented for better performance gains. Finally a hive-hbase table is created and we can see that performance improves by nearly 10-20 times when searching a particular record through hbase when compared to hive. 
