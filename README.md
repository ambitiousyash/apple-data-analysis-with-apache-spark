# apple-data-analysis-with-apache-spark

I used DataBricks to create multiple ETL pipelines using the Python API of Apache Spark i.e. PySpark.
I have used sources like CSV, Parquet, and Delta Table then used Factory Pattern to create the reader class. Factory Pattern is one of the most used Low-Level designs in Data Engineering pipelines that involve multiple sources.
Then wI used PySpark DataFrame API and Spark SQL to write the business transformation logic. In the loader part, I have loaded data into two fashion one using DataLake and another by Data LakeHouse

AIM:
1)To use databrick enivironment
  *create cluster
  *switch on DBFS(databrick file system)
  *upload required csv,parquet files
  *create delta table

2)to understand LLD(low level design) of writing good codebase in data engineering
  *undersatnd factory pattern
  *create one abstract reader which will use factory pattern

3)designing codebase
  *required extractor,transformer and load class
  *required utils class

4)spark concept
  *sparksession
  *row and column file formats
  *broadcast join
  *narrow vs wide transformation

5)different buisness logic
  *customer who have bought airpods after buying iphone
  *customers who have bought both airpods and iphone
  *list all the products bought by customers after their initial purchase

  
  
