# node-db
Custom Database - NodeJS Based Custom Database API A Modular Database like Couchbase but more modular

## Backends
This Implaments node-db-fs as reference
- node-db-fs
- node-db-couchbase
- node-db-mem
- node-db-fs


- create/insert, upsert/replace, update
- delete, remove, archiv
- lock
- query
- retrive/get, getMulti/batch, 


# Why?
There are diffrent types of userneeds and you want to choose the right Database Solution for your usecase

# How to Flexible Code and Grow a Database

## Early Stage
in the Early Stage there is not much that matters you want to store data for your Software and Start Coding

Create a /db folder and use the file-db-adapter written in node or go

### Optimizing the Early Stage

#### Failover 
if you got the need for failover its simply you do master slave replication with heartbeat monitoring all writes go to a master and reads can be spread across the nodes

#### driver
a database driver is simply some interface to your database that allows you working with it and maybe also handels managment.

### Schema, Model
When your data grows a Model is a cool extension it don't matters if you call it model or Schema. It Provides the Data Serialization Deserialization

### Use existing Technology
if your need grows you can build your own Database Stack based on Existing Software cool Combinations are
- MYSQL + SOLR Indexing

# Databases are a big Topic.

