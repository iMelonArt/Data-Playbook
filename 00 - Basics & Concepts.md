# Data & AI platform Overview

Data has always been valuable, but simply owning it isn't enough. The key is using data to gain meaningful insights for better decision-making.


## Data-related roles and definitions

| Roles | Definition |
| --- | --- |
|**Chief Data Officer (CDO)**| Manages and maintains databases. |
|**Database administrator(DBA)** | Manages and maintains databases. |
|**Data / Business / Business Intelligence (BI) Analyst** | Analyzes business processes and data to identify trends, create reports, and provide actionable insights for decision-making and strategy development. |
|**Data Scientist**| Extracts insights and builds predictive models from data using statistical analysis, machine learning, and data visualization techniques.|
|**Data Architect**| A practitioner of data architecture, a data management discipline concerned with designing, creating, deploying and managing an organization's data architecture.|
|**Data Engineer**| Designs, builds, and maintains data infrastructure, including pipelines and databases, to ensure data availability and reliability for analysis. |
|**Machine Learning Engineer**| ADevelops and deploys machine learning models into production, optimizing performance and scalability for real-world applications. |

## Structured vs Unstructured Data

According to Databricks and [MongoDB Research](https://www.mongodb.com/resources/basics/unstructured-data/structured-vs-unstructured), around 80% to 90% of data generated and collected by organizations is unstructured, and this is quickly growing. Due to this growth, mastering unstructured data management and data storage is critical.

## Common data file formats

What data formats and standards do you use in your data science projects? Let's summarize the common data formats used for storing and exchange data:

| Tabular Formats | Notes |
| --- | --- |
|CSV (Comma-Separated Values) | A simple, text-based format where each line represents a row of data, and columns are separated by commas ','. |
|TSV (tab-separated values) | A simple, text-based format and separated by delimiter. |
|Excel (XLS/XLSX)| A spreadsheet format used by Microsoft Excel, which can contain multiple sheets with rows and columns, as well as formatting, formulas, and charts. |

| Columnar Formats | Notes |
| --- | --- |
|Parquet | A columnar storage file format optimized for use with big data processing frameworks like Apache Hadoop and Apache Spark. It allows for efficient data compression and encoding, enabling faster query performance. |
|ORC (Optimized Row Columnar) | Another columnar storage format similar to Parquet, primarily used within the Hadoop ecosystem to improve the performance of reading and writing large datasets. |

| Hierarchical Formats | Notes |
| --- | --- |
|JSON (JavaScript Object Notation) | A lightweight, text-based format for representing structured data based on key-value pairs. It's widely used in web applications for data interchange between a server and a client.|
|XML (eXtensible Markup Language) | A flexible, text-based format that uses tags to define objects and their attributes. It's used for both data storage and transmission, especially in web services and configuration files. |

| Binary Formats | Notes |
| --- | --- |
|Avro| A binary format used for data serialization in Apache Hadoop. It supports schema evolution and is designed to be compact and efficient for both storage and transmission.|
|Protobuf (Protocol Buffers)| A language-neutral, platform-neutral binary format developed by Google for serializing structured data. It's used for communication protocols, data storage, and more.|

| Specialized Formats | Notes |
| --- | --- |
|HDF5 (Hierarchical Data Format version 5)| A binary format designed to store large amounts of data, supporting complex data relationships and metadata. It's commonly used in scientific computing.|
|Feather| A binary columnar data format optimized for use with Python and R, enabling fast read and write performance for large datasets.|

## A glimpse into the future
Apache Iceberg is an open-source high-performance format for huge analytic tables. Iceberg enables the use of SQL tables for big data while making it possible for engines like Spark, Trino, Flink, Presto, Hive, Impala, StarRocks, Doris, and Pig to safely work with the same tables, at the same time.


## The Road to Interoperability
Fundamentally, companies need to be able to have data interoperability to realize the benefits of the lakehouse.


Delta Lake Universal Format (UniForm) for Iceberg compatibility


## 3Vs - Big Data




## Top Data Challenges

According to Salesforce Research, security threats is the top 1 risk to Analytics & IT Leaders as well as the business leader. 

However, lack of data hormonization, different data structure, file formats and different sources. To achieve the data hormonization is the road to achieve the unifying disparate data fields, formats, dimensions, and columns into a composite dataset.

