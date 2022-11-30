# BigData-HBase

#Limitations of Hadoop
Hadoop can perform only batch processing, and data will be accessed only in a sequential manner. That means one has to search the entire dataset even for the simplest of jobs. A huge dataset when processed results in another huge data set, which should also be processed sequentially. At this point, a new solution is needed to access any point of data in a single unit of time (random access).

#Hadoop Random Access Databases
Applications such as HBase, Cassandra, couchDB, Dynamo, and MongoDB are some of the databases that store huge amounts of data and access the data in a random manner.

#What is HBase?
HBase is a distributed column-oriented database built on top of the Hadoop file system. It is an open-source project and is horizontally scalable. HBase is a data model that is similar to Google’s big table designed to provide quick random access to huge amounts of structured data. It leverages the fault tolerance provided by the Hadoop File System (HDFS). It is a part of the Hadoop ecosystem that provides random real-time read/write access to data in the Hadoop File System. One can store the data in HDFS either directly or through HBase. Data consumer reads/accesses the data in HDFS randomly using HBase. HBase sits on top of the Hadoop File System and provides read and write access.


#Features of HBase
HBase is linearly scalable.
It has automatic failure support.
It provides consistent read and writes.
It integrates with Hadoop, both as a source and a destination.
It has easy java API for client.
It provides data replication across clusters.

#Where to Use HBase
Apache HBase is used to have random, real-time read/write access to Big Data.
It hosts very large tables on top of clusters of commodity hardware.
Apache HBase is a non-relational database modeled after Google's Bigtable. Bigtable acts up on Google File System, likewise Apache HBase works on top of Hadoop and HDFS.

#Applications of HBase
It is used whenever there is a need to write heavy applications.
HBase is used whenever we need to provide fast random access to available data.
Companies such as Facebook, Twitter, Yahoo, and Adobe use HBase internally.
