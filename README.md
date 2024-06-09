# Data Lake Bootcamp: Building Reliable Data Lakes

https://www.oreilly.com/live-events/data-lake-bootcamp/0636920095503/0636920095502/

### Day 1: Learning Data Lake and Processing Data with Azure Databricks

In this session, you’ll learn what a data lake is, how it can be used to store and organize your data, and about related reference architectures like the Data Lakehouse and Medallion architecture. Then, you’ll learn how to set up a data lake in Microsoft Azure, and what options it has related to scalability, security, performance, and replication. Finally, you’ll learn how you can use Apache Spark to process large volumes of data. Azure Databricks is a Spark based platform, so you’ll use it to work with Spark. Here, you’ll first extract data from multiple file formats like CSV and JSON. And then you’ll clean and transform this data using various options in Spark.

### Day 2: Building Reliable Data Lake with Delta Lake

Delta Lake is an open-source storage layer that brings reliability to data lakes. In this session, you’ll first learn what Delta Lake is, how it handles metadata, and how it provides ACID guarantees to a data lake. You’ll then work on storing processed data as Spark tables in Delta format and understand its transaction log. You’ll also learn how to run SQL queries on data in your data lake. Lastly, you’ll learn about important features of Delta, including performing CRUD operations, schema enforcement, table constraints, and time travel. 

## Schedule
The timeframes are only estimates and may vary according to how the class is progressing.

### Day 1: Learning Data Lake and Processing Data with Azure Databricks (3 hours)

#### Introduction to Data Lake (45 mins)

Presentation: Understanding the data lake concept; challenges with data warehouses; data lake objectives; reference architecture to use data lake (data lakehouse and medallion); organizing data (raw, enriched, curated)
Group discussion: How organizations are handling data
Q&A
Break (5 minutes)

#### Using Azure Data Lake Gen2 to build Data Lake (40 mins)

Presentation and demos: Introduction to Azure Data Lake Gen2; scalability, performance and replication; setting up Data Lake Gen2 account; security options—access keys, SAS, Azure AD (RBAC)
Hands-on exercises: Create ADLS Gen2 account; set up permissions on storage
Q&A

#### Introduction to Apache Spark and Azure Databricks (40 mins)

Presentation and demos: Introduction to Apache Spark and its architecture; overview of Azure Databricks platform
Hands-on exercise: Set up Databricks workspace and cluster
Q&A
Break (5 minutes)

#### Extracting and transforming data from multiple file formats (45 mins)

Demos: Working with multiple file formats like CSV, JSON, and Parquet; reading data from data lake
Hands-on exercise: Apply operations to clean and transform data
Q&A

### Day 2: Building Reliable Data Lake with Delta Lake (3 hours)

#### Loading processed data to Data Lake (45 mins)

Presentation: Understanding Spark SQL and Spark tables
Hands-on exercises: Write processed data to data lake; store dataset as Spark tables; write SQL queries on data in data lake
Q&A
Break (5 minutes)

#### Introduction to Delta Lake (40 mins)

Presentation: Challenges with data lake; Delta format and transaction log; ACID guarantees on data lake; competitors
Group discussion: How Delta Lake can help build a data warehouse on data lake
Q&A

#### Storing Data in Delta format (30 mins)

Demos: Working with Delta format
Hands-on exercises: Creating and managing Delta tables; audit history; table constraints
Q&A
Break (5 minutes)

#### Using Delta Lake features (55 mins)

Demos: Working with Delta Lake features
Hands-on exercises: Perform CRUD operations, schema enforcement and evolution, time travel, and optimization; compare performance with Parquet
Q&A
