# DistributedTransparentMemory
DistributedTransparentMemory

This is the implementation of Distributed transparent memory in C, based on socket programming project. A distributed memory - adding up the main memory of several connected machines together to create a one big unified chunk of storage for the user - the locality information of the data is completely hidden from the user. Data stored by the user is hashed to the memory of of one of the connected backend node and resides there. Memory appear as local memory to the end user, though memory is distributed across several machines in the backend. User specify the necessary keys to fetch the data, the backend automatically finds the machine which hosts the requested data and fetch it to user. This is how Hadoop HDFS is designed. The exact problem statement is here.

NAME: ABHISHEK SAGAR
ROLL NO: 10305042
--------------------
NAME : LALIT KUMAR
ROLL NO : 10305073

INSTRUCTIONS:

RUN make file with arguments as no of nodes to be created.
eg: ./make 4

This will create 4 nodes, and will be launched. (you should be working on linux machine termainal, and not remote login)

see pdf file in this dir for details
