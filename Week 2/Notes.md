### Week 2

 **Types of data**
 1. Structured
 2. Semi-structured
 3. Unstructured


 Data comes in a wide-ranging variety of file formats, such as delimited text files, spreadsheets, XML, PDF, and JSON, each with its own list of benefits and limitations of use.  

Data is extracted from multiple data sources, ranging from relational and non-relational databases to APIs, web services, data streams, social platforms, and sensor devices.

**Languages for Data Analysts**
1. Querying languages, such as SQL, used for accessing and manipulating data from databases.

2. Programming languages such as Python, R, and Java, for developing applications and controlling application behavior.

3. Shell and Scripting languages, such as Unix/Linux Shell, and PowerShell, for automating repetitive operational tasks.
---
**Relational Database (RDBMS)**
- data is stored in tabular format with well defined relationship
- Advantages
  - create meaningful information
  - minimize data redundancy
  - ease of backup and disaster recovery
  - ACID compliant

---
**Non-Relational Databases (No-SQL)**
- Key-value Store
- Document Store
- Column-based Store
- Graph-based Store

- Advantages
  - ability to handle large volume of data of all kind of structure
  - ability to run as a distributed system scaled across multiple data centers
  - an efficient and cost-effective scale-out architecture
  - simpler design, better control over availability, and improved scalability

---
A **Data Repository** is a general term that refers to data that has been collected, organized, and isolated so that it can be used for reporting, analytics, and also for archival purposes.  

The different types of Data Repositories include:

Databases, which can be relational or non-relational, each following a set of organizational principles, the types of data they can store, and the tools that can be used to query, organize, and retrieve data.

Data Warehouses, that consolidate incoming data into one comprehensive storehouse.  

Data Marts, that are essentially sub-sections of a data warehouse, built to isolate data for a particular business function or use case.

Data Lakes, that serve as storage repositories for large amounts of structured, semi-structured, and unstructured data in their native format.

Big Data Stores, that provide distributed computational and storage infrastructure to store, scale, and process very large data sets.

---

**Datamarts, Datalake, and Datawarehouse**
1. Datawarehouse is the big branch of datamarts  
2. Datalake poses only raw-data

**Extract, Transform, and Load process (ETL)**
1. Gathering raw data
2. Extracting information needed
  - batch and stream processing
3. Cleaning, standardizing, and transforming data into usable format
4. Loading data into a data repository
  - initial loading, incremental loading, and full fresh

**5 Vs of Big Data**
1. Velocity
2. Volume
3. Variety
4. Veracity
5. Value
- Apache Hadoop, Apache Hive, and Apache Spark
