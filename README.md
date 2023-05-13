This project is a Python-based implementation of a distributed file system, which is inspired by the Hadoop Distributed File System (HDFS) and uses a similar 
architecture. The file system consists of a Master node (equivalent to HDFS NameNode) that stores the file system namespace, including information about files, 
blocks, and their mappings to minions (equivalent to HDFS DataNodes), and a set of Minion nodes that store the actual data blocks. A client is provided to communicate 
with the files.
