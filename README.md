# Decentralized Cluster-Based NoSQL DB System - Atypon Training Capstone Project Aug-Oct/2023

![](https://github.com/ibrahemjrr/Decentralized-Cluster-Based-NoSQL-DB-System/blob/main/Image.png)

A decentralized cluster-based architecture of the NoSQL database. In contrast to centralized systems, decentralized NoSQL databases distribute data and responsibilities across multiple nodes with no central manager node; instead, sophisticated schemas are employed to ensure data consistency and load balancing among the nodes.
- Document-Based Structure: The database follows a document-based model, where JSON objects are used to store and organize data.
- Collections: Each database has many collections, and every document within a database adheres to a JSON schema associated with that particular collection.
- Supported Queries: Database queries encompass a range of actions, including Reading, Updating Creating or Deleting databases, Collections or Documents.
- Index Creation: The system supports the creation of indexes, thus enhancing query performance.
- Data Consistency: After a write operation, the node with affinity must broadcast the data change to other nodes, during this process, if a read query occurs on any node, it may read the older version of the data.
- Users are distributed across nodes in a load-balanced manner, also document affinities as mentioned previously.

### for more info & explanation check the [Report](https://github.com/ibrahemjrr/Decentralized-Cluster-Based-NoSQL-DB-System/blob/main/Final%20Report.pdf) file.
